# Angelo's rclone uploader

A personal command-line tool that copies large files, such as screen recordings of software tests, from the developer's own computer to a Google Drive folder. It uses [rclone](https://rclone.org/), an open-source file transfer program, with a personal OAuth client.

## What it does

- Signs in with a Google account through the standard Google consent screen.
- Requests only the `drive.file` scope. The tool can see and change only the files and folders it creates itself, not the rest of the Drive.
- Copies files from the user's computer to one Drive folder. It does not delete or overwrite files outside that folder.

## Who can use it

The developer and the people they share a folder with. This is not a public service, and there is nothing to sign up for.

## Privacy policy

[Read the privacy policy](https://gist.github.com/AngeloBenjamin0/d63a56394cf4f590db4a7214789df83c)

## Contact

Open an issue on this repository or write to angelofaria060@gmail.com.

This tool is independent. It is not provided or endorsed by Google or the rclone project.
