# luxus-icons
The Luxus Group's icons in a FontAwesome format.

## Installation

1. Make sure the `fonts` folder is copied to your _CDN_ or _assets_ folder of
your application.
1. Set the `$luxus-icons-font-path` variable to the path you defined above,
e.g. `$luxus-icons-font-path: '/assets/fonts/luxus-icons';` (SCSS), e.g.
`@luxus-icons-font-path: '/assets/fonts/luxus-icons';` (LESS)
1. Import the appropriate `luxus-icons.scss` or `luxus-icons.less` file into
your application.
1. Double check that your server's log is not posting any 404 errors as in
not being able to find your font files.

## Example Usage

    <i class="fa fa-laulea-flower"></i>
    <i class="fa fa-luxus-diamond"></i>
    <i class="fa fa-panico-olives"></i>
