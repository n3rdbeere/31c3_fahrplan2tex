# Create Herald Cards for the Chaos Communication Congress 2014

This Parser creates Cards using the Data of the Fahrplan

## Dependencies

This parser is written in Perl and needs the library 

`JSON::Parse 'json_file_to_perl'`

And the Fahrplan-data provided as json-file in this directory, named

`schedule.json`

It also uses LaTeX, only core packages are needed here.

## Usage

clone the repository and hit `perl fahrplan2tex.pl`

It will create a pdf named as the event-ID of each event in a directory named after the version of the schedule.

