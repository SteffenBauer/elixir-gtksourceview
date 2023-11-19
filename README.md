elixir-gtksourceview
====================
![gedit](https://raw.githubusercontent.com/SteffenBauer/elixir-gtksourceview/master/elixir_gedit.png)

GtkSourceView syntax highlighting for the [Elixir programming language](http://elixir-lang.org/)

Covers Elixir version 1.15.x

## Usage: 

Copy `elixir.lang` into one of these directories: 

 * `~/.local/share/gtksourceview-X.X/language-specs/`
 * `/usr/local/share/gtksourceview-X.X/language-specs/`
 * `/usr/share/gtksourceview-X.X/language-specs/`

Replace 'X.X' with your version of GtkSourceView.

_gedit_ and other tools using GtkSourceView should then show Elixir syntax highlighting.

Versions for older Elixir releases can be found in `old_versions`

Have also a look at [elixir-ctags](https://github.com/mmorearty/elixir-ctags) to further enhance your gedit experience when writing Elixir code.

## Please note:
I reorganized the language definition file in order to include an experimental setup. It should now highlight ExUnit language elements only in the according context of elixir unit testing files. Please submit an issue report should you encounter any problems.

### License

This language definition file is licensed under the GNU Lesser General Public License 3.0.

A copy is provided with this package (see LICENSE) or can be obtained at:

http://www.gnu.org/licenses/lgpl-3.0.html

This language definition file is to be used with GtkSourceView

GtkSourceView is free software; you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation; either version 2.1 of the License, or (at your option) any later version.

GtkSourceView is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with this library; if not, write to the Free Software Foundation, Inc., 51 Franklin St, Fifth Floor, Boston, MA  02110-1301  USA
 
