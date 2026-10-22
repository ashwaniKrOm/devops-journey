### bash script ends with '.sh' However it can run fine without '.sh' extension.

## shebang :-
- #!/bin/bash
- Bash script starts with shebang
- shebang is combination of bash '#' and bang '!' followed by bash shell path '/bin/bash'
- shebang tells the shell to execute this script via bash shell.
- shebang is absolute path to bash interpreter
<img width="422" height="122" alt="image" src="https://github.com/user-attachments/assets/f59afc92-6b41-491f-82cb-94cfeb5d435f" />

## Execute Script
- assign execution rights using 'chmod' and run via any of below three methods
- sh test.sh
- bash test.sh
- ./test.sh
<img width="377" height="206" alt="image" src="https://github.com/user-attachments/assets/d446006a-cb60-4d8b-b4b9-40c22fc07ef4" />

## Comments in bash script
Any line starts with '#' is a comment and will be ignored by interpreter.

## Variables and DataTypes in Bash :-
There is no datatype in bash, a variable is capable of storing numeric, char or string
- Variable should start with letter or underscore '_'
- Variable name can contain letters, numbers and underscore
- Variable name are case-sensitve
- Valid Exp: count, name, _var, myNm, MY_NAME, _Abc123
- Invalid Exp: 4thVar, my nm, my-nm
- Don't use reserved keyword as variable

  <img width="273" height="410" alt="image" src="https://github.com/user-attachments/assets/586e8fa9-a1e8-46bf-85c6-cfe47b377cf8" />


## Input and Output in bash scripts :-
### Input :
- reading user input and storing in variable
- command line arguments
- reading from file
<img width="396" height="373" alt="image" src="https://github.com/user-attachments/assets/387d7185-d42a-4a60-a2bf-355c84a0c916" />

### Output :
- Display using 'echo'
- Display using 'printf'
- Write output to a file '>'
- Append to a file '>>'
<img width="443" height="327" alt="image" src="https://github.com/user-attachments/assets/6f2c5ad7-7d05-4ef1-bfe7-ba7fdc397be1" />
