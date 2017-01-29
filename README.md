# flac-to-mp3

A Python script for mass converting FLAC files to MP3 V0 using ffmpeg

## Purpose

This script is designed to mass convert flac files with minimal input from the user.

## Setup

You must have ffmpeg in your system PATH, as it is used to do the actual conversion.

## Usage

To run script on current working directory:

```bash
./flac-to-mp3
```

Or, alternatively, to specify a directory:

```bash
./flac-to-mp3 root_directory
```

The script searches recursively in the directory and attempts to convert all files ending in '.flac' to MP3, using MP3 V0 for extremely high fidelity and minimal file size. The converted files are placed in `root_directory/MP3/path/to/file.mp3` (the originals are left untouched, of course).

