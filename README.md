# where-to-fly

This is a personal project with the aim of both learning how to design, develop and deploy a project, as well as setting up a little tool to help (feed) my other hobby (obsession): flight simulation.

The project should be designed in multiple phases that build on each other to create a tool that can help me choose where to fly.



The tool should ultimately :

- Run natively on Windows, initially on the command line, ultimately in a user interface

- Output an airport, identified at least by its 4-letter ICAO code, that is modelled in MSFS 2024 and landable

- "Remember" which airports have been flown to or discarded and not output it

- Accept an "airplane" parameter, which if populated will restrict the ouput to airport that airplane can land on

- Accept a "departure airport", which if populated will restrict the output to an airport within an, at first, set distance of said departure airport