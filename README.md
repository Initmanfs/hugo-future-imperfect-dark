# Hugo Future Imperfect Dark

This theme is based on [Future Imperfect](https://github.com/jpescador/hugo-future-imperfect) by [Julio Pescador](https://github.com/jpescador)

Future Imperfect Dark is a responsive theme tailored for blogging. The name is no coincidence which is a port of [HTML5 UP's theme](http://html5up.net/future-imperfect). Some extra features have also been implemented to assist you.

![Hugo Future Imperfect Screenshot](https://gitlab.com/initmanfs/theme/raw/master/images/screenshot.png)

## Getting Started

Run the following commands in your Hugo site directory:

    mkdir themes
    cd themes
    git clone https://github.com/jpescador/hugo-future-imperfect.git

A folder called hugo-future-imperfect will be created. Navigate to this folder.

## The Config File

The file contains comments on the functionality for each param. Please see the file for more information.

## Shortcodes
The theme also contains the following [shortcodes](https://gohugo.io/extras/shortcodes/) that I hope you find useful: img-post, img-fit, and url-link.  

### Image post
img-post: allows the user to add an image which can be placed in the center, to the left, or the right. The commands are shown below:

    - Named
    {{< img-post path="date" file="filename.jpg" alt="Alt Text" type="left" >}}

    - Positional
    {{< img-post "title" "filename.jpg" "Alt Text" "left" >}}

Please refer to the img-post shortcode file for more information on the parameters

### Multiple Image Post
img-fit: allows user to insert multiple images with the ability to create a gallery if needed. The command is shown below and is positional only:

    {{< img-fit
        "4u" "pic04.jpg" "Alt text"
        "4u" "pic05.jpg" "Alt text"
        "4u$" "pic06.jpg" "Alt text"
        "date" >}}

Please refer to the img-fist shortcode file for more information on the parameters


### URL link
url-link: create a hyperlink and add a target value to the link. _blank will be used by default if a target value is not set. The shortcode is positional only.

    {{< url-link "Hugo" "http://gohugo.io/" >}}

Position 0 will be the link text. 1 will be the url and the last position will be value of the target attribute.

## View the theme on Hugo's built-in server

Run the following command to view the content of the website:

    hugo server

You can now view the website at the following link, [localhost:1313](http://localhost:1313)

## License

This theme is released under the GNU GPLv3 license. Please read the [license](https://gitlab.com/initmanfs/theme/blob/master/LICENSE.md) for more information.
