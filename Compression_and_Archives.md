# Compression and Archives

* [zip](#zip) - package and compress (archive) files
* [unzip](#unzip) - list, test and extract compressed files in a Zip archive

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
