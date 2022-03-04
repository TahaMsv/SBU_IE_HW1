
# Cool Compiler
This project is developed for SBU Compiler Design Course - Fall 2020 

<!-- TABLE OF CONTENTS -->
# Table of Contents
1. [About The Project](#AboutTheProject)
2. [Auxiliary Tools](#AuxiliaryTools)
3. [How To Use](#HowToUse)
4. [Roadmap](#Roadmap)
5. [Contributing](#Contributing)
6. [License](#License)

<!-- ABOUT THE PROJECT -->
## About The Project <a name="AboutTheProject"></a>



It has 3 Phases that in each phase the focus is on a specific part of a real compiler.
- Phase 1 (Scanner)
- Phase 2 (Parser)
- Phase 3 (Code Generator)


> This project is not a full compiler at all!
> It is just a simple implementation of a compiler (with many bugs :) ) based on lessons of the course and course assistant team's rules

<p align="right">(<a href="#top">back to top</a>)</p>   



## Auxiliary Tools <a name="AuxiliaryTools"></a>

In this project, we use some useful libraries and projects to make implementation easier.

* [Jflex -  Lexical Analyzer Generator](https://www.jflex.de/)
* [PGen  -  Graphical LL(1) Parser Generator ](https://github.com/Borjianamin98/PGen)
* [SPIM  -  Simulator For Programs Written For MIPS R2000/R3000 Processors ](http://spimsimulator.sourceforge.net/)
<p align="right">(<a href="#top">back to top</a>)</p>


## How To Use <a name="HowToUse"></a>
In Each Phase, There Are Some Necessary Tasks For Running The Program.

* Phase 1 : 
[test.txt](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase1/src/test.txt) Is The Input File For Scanner. You Just Need To Change This File For Testing More Inputs. You Can Also See The Result In [output.html](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase1/src/output.html)

* Phase 2 : In This Phase We need [InputCoolFilePath](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase2/PROJECT/test/in) And [OutputFilePath](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase2/PROJECT/out/result) And [TablePath](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase2/PROJECT/src/table.npt) You Can Change Each Of Them For Different Tests. To Run The Program, You Should Run  [Main.java](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase2/PROJECT/src/Main.java) Like Below     &emsp; &emsp; &emsp; &emsp; &emsp;&emsp; java [javaClassFile] --input [inputCoolFilePath] --output [outputFilePath] --table [tablePath]

* Phase 3 : You Should Just Run [Main.java](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase3/PROJECT/src/Main.java). The SPIM Output Will Be Created In [code.s](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase3/PROJECT/src/code.s).  You Can Also Change Input File (Cool Program) [test.cool](https://github.com/Aminsaveh/SBU_IE_HW1/tree/main/SBU_Compiler/Phase3/PROJECT/src/test.cool)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap <a name="Roadmap"></a>

- [ ] Fix Scanner Problems (Phase 1)
- [ ] Change Graph For Accepting All Declarartions And Assignments In Any Order (Phase 2)
- [ ] Add Array Support (Phase 3)
- [ ] Fix Logical Computations (Phase 3)
- [ ] Clean The Project :) (All Phases)

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- Contributing -->
## Contributing  <a name="Contributing"></a>

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License <a name="License"></a>

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>
