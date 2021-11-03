# Laboratory Work №3

List of valid keys:
+ -h, --help, getting help;
+ -v, --verbose, enable verbose mode of program;
+ -l, --my_list, list of values;
+ -b, --my_boolean, optional flag;
+ -f, --my_file, saving file;

### Commands usage
`./main`

`./main -h`

`./main --help`

`./main --verbose=4`

`./main -v 1`

`./main --my_list=3,4,5,6`

`./main -l 1,2,3,4`

`./main --my_file="some_text"`

`./main -f "some_text"`

`./main --my_boolean=0`

`./main -b=1`

### In case of wrong key
`./main -k --notify`
`./main: invalid option -- 'k'`
`./main: unrecognized option '--notify'`
