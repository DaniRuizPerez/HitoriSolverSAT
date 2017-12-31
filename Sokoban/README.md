Predicate Calculus Theorem Proving (using Prover9)
============

This theorem proving assignment is one of the projects that I developed for the Knowledge Representation and Automatic Reasoning course in the junior year of my undergrad in computer science at UDC (Spain). It will check whether a conclusion follows from the premises using a theorem prover for Predicate Calculus called Prover9. This software accepts a list of formulas in First Order Logic and decides whether a formula is valid or not by refutation using resolution.




Uninformed search.

search.c contains the code for tree search extracted directly from the Russell&Norvig03's book. To construct the corresponding domain, it is necesary to define the funtions specified in the search.h file.

8puzzle.h contains the definition of the type tState (description of the state of a problem) and the actions we can execute. 8puzzle.c contains the code for the functions described in search.h.

search.c expects the domain definitions from the files domain.h and domain.c. An option to change form one domain to another is to copy 8puzzle.h and 8puzzle.c to domain.h and domain.c respectively. With the makefile we simplify the symbolic link creation process. To stablish a domain, we execute:

```
make domain DOM=8puzzle
```
That creates the symbolic link, stablishing 8puzzle as the domain. To compile the program we then just execute

```
make
```
Storing the executable in the file search.


8puzzle.c y h son los domain.c y .h








## Contact

Contact [Daniel Ruiz Perez](mailto:druiz072@fiu.edu) for requests, bug reports and good jokes.


## License

The software in this repository is available under the GNU General Public License, version 3. See the [LICENSE](https://github.com/DaniRuizPerez/AutomaticReasoning/blob/master/LICENSE) file for more information.