# science-exam #

A template and example for how to create multiple versions of exams for students using randomly generated values.

Currently uses XeLaTeX

## Explanation of Package Choices ##

### Exam Document Classes ###
* [acroweb – Scripts to create interactive tests from a database](https://www.ctan.org/pkg/acroweb) using [acrotex – The AcroTEX education bundle](https://www.ctan.org/pkg/acrotex)
* [exam – Package for typesetting exam scripts](https://www.ctan.org/pkg/exam)
* [exam-n – Exam class, focused on collaborative authoring](https://www.ctan.org/pkg/exam-n)

* [Exam design – LATEX class for typesetting exams](https://www.ctan.org/pkg/examdesign)
* [exerquiz – Environments for defining exercises and quizzes](https://www.ctan.org/pkg/exerquiz) using [acrotex – The AcroTEX education bundle](https://www.ctan.org/pkg/acrotex)
* [exam209 – Process exam questions and answers (LATEX 2.09)](https://www.ctan.org/pkg/exam209)
* [exams – Typeset exam questions](https://www.ctan.org/pkg/exams)
* [exsheets – Create exercise sheets and exams](https://www.ctan.org/pkg/exsheets)
* [knst – Multiple-guess tests](https://www.ctan.org/pkg/knst)
* [mathexam – Package for typesetting exams](https://www.ctan.org/pkg/mathexam)
* [QCM – A LATEX2ε class for making multiple choice questionnaires](https://www.ctan.org/pkg/qcm)
* [esami – Typeset exams with scrambled questions and answers](https://www.ctan.org/pkg/esami)
* [probsoln – Generate problem sheets and their solution sheets](http://ctan.org/pkg/probsoln)
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()
* []()


#### Resources ####
* [CTAN Topic exam](https://www.ctan.org/topic/exam)
* [CTAN Topic exercise](http://www.ctan.org/topic/exercise)
* [Rolling your own Document Class: Using LATEX to keep away from the Dark Side](https://www.tug.org/TUGboat/tb28-1/tb88flynn.pdf)

### Randomization Options ###

* [`rangen` package](http://www.ctan.org/pkg/rangen)

### Calculations ###

* [CTAN Topic calculation](http://www.ctan.org/topic/calculation)
* `fpu` library in [PGF/TikZ](http://www.texample.net/tikz/)
* [fp – Fixed point arithmetic](http://www.ctan.org/pkg/fp)
* [minifp – Fixed-point real computations to 8 decimals](http://www.ctan.org/pkg/minifp)

### Problem Database ###

* See `probsoln` above.
* [Exercises lists management in LaTeX](https://github.com/Domlol/texomaker)
* 

### Rubric Options ###

Many of the available document classes for writing examinations focus
on points, but I grade students according to standards for what they
should know according to Standards Based Grading (SBG). The best
option is probably to code my own rubric. I desire the following
features:

*  *Transparency*. The standard should be named, at least in an
abbreviated form.
* *Self-Evaluation*. There should be a place for the student to
self-evaluate.
* *Ease of Feedback*. The format should make it easy for the teacher
to give whatever feedback is needed.


