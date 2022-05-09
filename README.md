# ansible

## Inventory 
Inventory is text file, then entries in the inventory can an IP address or DNS name

#
XML

<courseName>DevOps</courseName>
<trainerName>kishan</trainerName>
<trainees>
    abc@gmail.com
    def@gmail.com
</trainees>
<timing>
    <morning>6AM</morning>
    <evening>7PM</evening>
</timings>

JSON

{
 "courseName": "DevOps",
 "trainerName": "kishan",
 "tarineers": [
    "abc@gmail.com"
    "def@gmail.com"
],
"timing": {
    "mornig": "6AM"
    "evening": "7PM"
 }

}



YAML
courseName: DevOps
trainerName: kishan
trainees
  - abc@gmail.com
  - def@gmail.com
timing:
  morning: 6AM
  evening: 7PM

###
MARKUP Language will have data as
KEY - VALUE (Regular key value)
KEY - MULTIPLE VALUES (List) (ex: trainees)
KEY - KEY -VALUE (MAP, DICT) (ex: timing )