=== sudoku_wp ===
Contributors: oreste
Donate link: http://oreste.parlatano.org
Tags: sudoku
Requires at least: 2.0.2
Tested up to: 3.1
Stable tag: trunk

include a sudoku grid ready to play in a page or article with the following code [sudoku_wp options]

== Description ==

- Introduction
 
As the plugin name indicates, Sudoku WordPress plugin allows to play the homonymous game.
It displays a grid 9×9 cells, composed by 9 sub-grids 3×3 cells. It generates a random sequence at the first sub-grid top left, then calculates the remaining 8 sub-grids. It fills the whole grid according to level of difficulty chosen through the appropriate plugin option.
It allows to regenerate the grid as much times as the user wishes just by reloading or refreshing the page. Once the grid is generated, displays two buttons, the first shows a hint, the other shows a complete solution.
 
- How it works
 
The plugin starts by showing a grid 9×9 cells partially filled with numbers and partially with blank cells where the user can input guessed numbers. Two buttons will also appear: “Hint” and “Solution”. By pressing “Hint” the guessed numbers will change their colour according to the guess, a correct guess will show the guessed number with green colour, a wrong guess will result with a red colour. By pressing “Solution” all the grid will be filled with the correct numbers.
The cells background colour can be set through the plugin options.
 
- How to use the plugin
 
Insert in a page or article the following code:
 
[sudoku_wp options]
 
where “options” is a list of options comma separated.
 
Example: [sudoku_wp 5,white,blue,28,Arial,540,black,yellow,100]
 
Available options are:
 
holes:  number of holes per row (min 2, max 6)
colo:   colour of sudoku numbers
back0:  background colour of sudoku table
fsiz:   size of sudoku numbers in pixels
ffam:   font-family of sudoku numbers
side:   physical size of sudoku 9×9 square plus buttons in pixels
bucol:  colour of buttons font
buback: colour of buttons background
bumar:  margin left of buttons

== Installation ==

1. Upload `plugin-name.php` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Place [sudoku_wp options] in your page or article

== Frequently Asked Questions ==

How I insert the Sudoku grid in a article or page?

See the example:
[sudoku_wp 5,white,blue,28,Arial,540,black,yellow,100]

== Screenshots ==

sudoku_wp_01.jpg

== Changelog ==

No changes

== Upgrade Notice ==

No upgrades


== Links ==

Doc page at: http://oreste.parlatano.org/wp/?p=64

Working exaple at: http://oreste.parlatano.org/wp/?p=68