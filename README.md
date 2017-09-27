#### Disclaimer: This is a very early stage in the process of greely, key functions don't work, just the shell of the program is running, production will continue in Q3-17.

![alt text](https://raw.githubusercontent.com/keybraker/Lexical-Grammatical-Analyzer-for-Greek/master/greely%20logo.png)

# Lexical and Grammatical Analyzer for Greek with the use of Flex Bison

A new way to interpret and understand natural human language.
Greek as first language to be worked on.
Ai that understands and learns the human language and you.

## Getting Started

Just clone the project to your computer and run make, it's simple as that !

```
git clone https://github.com/keybraker/greek-Ai-Bot.git
```

### Prerequisites

Most Linux distros and Mac OS come preinstalled with all of the following compilers
but if you find any trouble, these are the links to follow:

* gcc - https://gcc.gnu.org
* flex - https://www.gnu.org/software/flex/
* bison - https://www.gnu.org/software/bison/

➽ In the end only gcc will be needed

### Installing

```
git clone git@github.com:keybraker/Lexical-Grammatical-Analyzer-for-Greek-with-Flex-Bison.git
```
enter the project folder via terminal

```
run command "make"
```
to clean all products created by the program run command 
```
make clean
```

### Break down into end to end tests

The default input is "Καλημέρα, με λένε Ιωάννη και μαρέσει το ποδόσφαιρο."
If the default text is run, you will get the following outcome:

```
Kαλημέρα (ουσιαστικό, ενικού αριθμου , γένος θηλύκο , ονομαστική πτώση) κόμμα (σημείο στίξης) με (επεξηγηματικός σύνδεσμος) λένε [λέ] Ιωάννη (όνομα) και (συμπλεκτικός σύνδεσμος) μαρέσει [μα] το (οριστικό άρθρο γένους ουδέτερο ενικού) ποδόσφαιρο (ουσιαστικό, ενικού αριθμου , γένος ουδέτερο , ονομαστική πτώση) τελεία (σημείο στίξης) 
```

## Built With

* [c](https://gcc.gnu.org/) - The merging of all the parts and for database generation
* [flex](https://www.gnu.org/software/flex/) - The Lexical Analysis
* [bison](https://www.gnu.org/software/bison/) - The Grammatical Analysis

## Contributing

Please read [CONTRIBUTING.md](https://github.com/keybraker/Lexical-Grammatical-Analyzer-for-Greek-with-Flex-Bison/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.
➥ https://keybraker.github.io/Lexical-Grammatical-Analyzer-for-Greek/

## Versioning

I use [SemVer](http://semver.org/) for versioning. For the versions available. 

## Authors

* **Ioannis Tsiakkas** - *(Keybraker)* - [Keybraker](https://github.com/keybraker)

## License

This project is licensed under the Tsiakkas License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [CypressA](https://github.com/CypressA/GreekLex-2)
