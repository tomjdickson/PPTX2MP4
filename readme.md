# PPTX2MP4 - Convert PowerPoint files to MP4 using Python & Win32com

## Introduction
Not long ago I was looking for a simple method to convert PowerPoint PPTX Files to MP4s. This functionality unfortunately cannot be achieved natively in Microsoft PowerPoint (as of 9th of Jan 2020).

## Usage

### Installation
1. Clone the repo `git clone https://github.com/tomjdickson/PPTX2MP4.git`
2. Change directory `cd PPTXMP4`
3. Install dependencies `pip install -r dependencies.txt`
- Or manually install the dependencies:
- Win32Com `pip install pywin32`

Note if you recieve the following error message.
> Could not find a version that satisfies the requirement pywin32>=223 (from pypiwin32) (from versions:)
No matching distribution found for pywin32>=223 (from pypiwin32).

An upgrade to pip is required `pip install --upgrade pip`

### Configuration

### CLI


## TODO
There is a lot left for me to do here. The todo will be updated shortly.
1. Add configuration file to contain:
- Path for file to be extracted
2. Add CLI parameters that override the configuration file
3. Log file - Output of every run will populate the log file.
4. API - I want to wrap this in an API to allow people to use my website to convert their files via the web. This will be added to the examples folder.

## Support
