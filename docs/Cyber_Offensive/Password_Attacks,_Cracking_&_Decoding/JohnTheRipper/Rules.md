!!! info ""

    ```shell
    # Predefined rules
    --rules:Single
    --rules:Wordlist
    --rules:Extra
    --rules:Jumbo # All the above
    --rules:KoreLogic
    --rules:All # All the above
    # Create a new rule in John.conf
    [List.Rules:Tryout]
    l
    u
    ...
    | Rule          | Description                                               |
    |------------	|-------------------------------------------------------	|
    | l          	| Convert to lowercase                                  	|
    | u          	| Convert to uppercase                                  	|
    | c          	| Capitalize                                            	|
    | l r        	| Lowercase the word and reverse it                     	|
    | l Az"2015" 	| Lowercase the word and append "2015" at the end       	|
    | d          	| Duplicate                                             	|
    | l A0"2015" 	| Lowercase the word and append "2015" at the beginning 	|
    | A0"#"Az"#" 	| Add "#" at the beginning and the end of the word      	|
    | C          	|  Lowercase the first char and uppercase the rest      	|
    | t          	| Toggle case of all char                               	|
    | TN         	| Toggle the case of the char in position N             	|
    | r          	| Reverse the word                                      	|
    | f          	| Reflect (Fred --> Fredderf)                           	|
    | {          	| Rotate the word left                                  	|
    | }          	| Rotate the word right                                 	|
    | $x         	| Append char X to the word                             	|
    | ^x         	| Prefix the word with X char                           	|
    | [          	| Remove the first char from the word                   	|
    | ]          	| Remove the last char from the word                    	|
    | DN         	| Delete the char in position N                         	|
    | xNM        	| Extract substring from position N for M char          	|
    | iNX        	| Insert char X in position N and shift the rest right  	|
    | oNX        	| Overstrike char in position N with X                  	|
    | S          	| Shift case                                            	|
    | V          	| Lowercase vowels and uppercase consonants             	|
    | R          	| Shift each char right on the keyboard                 	|
    | L          	| Shift each char left on the keyboard                  	|
    | <N         	| Reject the word unless it is less than N char long    	|
    | >N         	| Reject the word unless it is greater than N char long 	|
    | \'N         	| Truncate the word at length N                         	|
    ```
