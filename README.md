# Temperature Converter CLI

Converts temperature between Fahrenheit and Celsius.

## Usage

Compile with `go build -o temp`.

Then, invoke the binary passing as argument the unit of temperature we want to convert **from**.
For example:

`./temp C` to convert from Celsius to Fahrenheit or `./temp F` to convert from Fahrenheit to Celsius.

## test
go test -v ./
go test -v -run M1
go test -v -run M2
## build
go build -o temp

