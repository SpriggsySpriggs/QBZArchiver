# QBZArchiver
Uses __DEFLATE$ compression from QB64 to create a file that can later be unzipped and retain the original file name.
QB64 v1.4 introduced a compression algorithm which allows you to compress a string. This program utilizes that function and writes the compressed string to a file and encoding the original file name. The program does not overwrite any files and instead renames the output files to "file(n).ext" (where n equals the number of the copy) similar to how Windows renames a file if you download one that is already named the same as the locally stored version.
