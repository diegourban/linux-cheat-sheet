# Compression and Archives

* [zip](#zip) - package and compress (archive) files
* [unzip](#unzip) - list, test and extract compressed files in a Zip archive
* [tar](#tar) - the GNU version of the tar archiving utility

## zip

#### Description
Zip is a compression and file packaging utility.

#### Options
* `-q` - quit mode, without log
* `-r` - travel the directory structure recursively

#### Examples
* `zip file.zip file.txt`
* `zip -q file.zip file.txt`
* `zip -r output.zip folderToZip/`

## unzip

#### Description
Unzip will list, test and extract files from a Zip archive.

#### Options
* `-q` - quit mode, without log
* `-l` - list archive files

#### Examples
* `unzip file.zip`
* `unzip -l file.zip`

## tar

#### Description
Tar stores and extracts files from a tape of disk archive.

#### Options
* `-c` - create a new archive
* `-z` - zip it
* `-x` - extract an archive
* `-f` - use archive file
* `-v` - verbosely list files processed

#### Examples
* `tar -cz folderToArchive > output.tar.gz` - create a zipped compression from the folder and output it to the file
* `tar -xz < archiveToExtract.tar.gz` - extract the zipped content incoming from the file
* `tar -czf output.tar.gz folderToArchive/`- create a compression and zip to the file the content from the folder
* `tar -xzf output.tar.gz` - extract the zipped content from the file
* `tar -vxzf output.tar.gz` - extract the zipped content from the file logging the list of files
