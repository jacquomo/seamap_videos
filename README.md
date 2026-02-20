Creating short promotional clips from BRUV imagery annotated in Eventment Measure for Seamap Australia
Written by jacquomo.monk@utas.edu.au and Justin.Hulls@utas.edu.au

This code assumes you have a folder containing all video files in a directory called "Converted". It also requires the following database export files from EventMeasure: "\\Points.txt","\\3DPoints.txt" and "\\Period.txt" and one "\\Metadata.csv" file that is structured based on GlobalArchive standards found in the CheckEM user guide https://marine-ecology.shinyapps.io/CheckEM/

This repo contains three code files that produce consistently formated video clips and metadata to allow upload into Seamap Australia:
- highlight_clips extracts video snippets for highlight events tagged using "Attribute 9" and short (<50 characters) plain text description in "Comment" attribute in EventMeasure exports (requires "\\Metadata.csv" and "\\3DPoints.txt")
- maxn_clips extracts video snippets at MaxN events based on EventMeasure exports  (requires "\\Metadata.csv" and "\\Points.txt")
- representative_clips extracts representative video snippets based on EventMeasure exports  (requires "\\Metadata.csv" and "\\Period.txt")

Once exported, use this token to transfer videos for ingestion into Seamap Australia: https://www.dropbox.com/request/CKLcIekGzVEoMB620k4Y

Reporting Issues:
If you encounter any errors or issues with the R code, please report them to jacquomo.monk@utas.edu.au.

This project is licensed under the MIT License:
Copyright (c) 2024 Jacquomo Monk

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
