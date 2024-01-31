# File Organizer Python CLI Script

A script to organize your files in a particular directory.

## Motivation

While learning Web development to create a portfolio website. I noticed that my downloads folder was so populated that i had to search again for the files which i had downloaded (pdfs, assets for the website and etc) so i wanted a one line solution which could replace my clicking, dragging and dropping workflow while decluttering the directory.

### Goal

To organize only files in a given directory into a general directory structure(i.e Documents, Videos, Images and etc) based on the file extension.

Have general files organize according to the extension map present in the script. But if some extensions are missing it will prompt the user to write the directory name for the type of file with a certain extension to be moved in.

## Usage

1. Clone this directory into a preferred location on your device (copy this command in your terminal)
```bash
    git clone https://github.com/AlphaCeph-C3/file_organiser_script.git .
```
2. Change the file permissions to make it executable:
```bash
    chmod +x file_org
```
3. Open the terminal in that folder where you are present or navigate to it and run the following command:
```bash
    ./file_org <Path to the directory you want to organize>
```
>       e.g: ./file_org /home/AlphaCeph-C3/Downloads # for unix like systems

4. you can have the cli interface for this script
```bash
    >>>./file_org -h      # <-type only this line in your terminal
    usage: ./file_org [-h] [dir]

    Organize files in a given directory according to their file extensions

    positional arguments:
      dir         absolute path to the directory you want organized

    options:
      -h, --help  show this help message and exit
```

>if you have basic files like the mp4, mp3, pdf, docx then it will work without any prompt. But if you have files with extensions which are not present in the ext_map dict in the script then you will be prompted to explicitly provide the name of the directory you want that file to be moved to in the same directory.

I made this as a cli script keeping in mind that i needed a one line solution.


### Contributing Guidelines

Please raise an issue and create a pull request to main branch only


