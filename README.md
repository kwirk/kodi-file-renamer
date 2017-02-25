kodi-file-renamer
=================

Rename files based on _Kodi_ database. Currently only works with the _MyVideo_ database, renaming files on the file system and updating the database accordingly.

This is designed around pretty basic file layout (e.g. single file per video; no stacking; no subfolders; no NFO files; no artwork files; etc.) where only _Kodi_ scrapers are used to get meta data. Therefore this may break on complex file layouts.

Currently file name changes for movies are in format "_title_ (_year_)", TV show folders "_title_" and episodes "_showtitle_ SxxExx - _episodetitle_".

Keep sure a backup is made of the database before using.
Use the `--dry-run` option to see what changes will be made.
And capture standard output of file renames so you have a record in case you wish to restore the database and revert changes.

License
-------
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
