Description: Advanced getopt functionality to use in shell programs.

Really configurable in each run:
- multiple short and long options for each variable,
- indicators: affirmative and negative forms,
- array of values for a parameter (bash arrays),
- choice list,
- default values for any parameter,
- positional parameters (some or all of them, configurable),
- required parameters,

Results:
- result will list not used variables, if specified;
- result will unset not used variables, if specified;
- result will list the rest of command line,
