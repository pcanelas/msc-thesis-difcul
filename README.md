# How To Deal with the Master Thesis 101 

## Frequently Asked Questions (FAQ)
These are Frequently Asked Questions (FAQ) created by and to MSc. students doing their thesis at the Departamento de Informática, Faculdade de Ciências da Universidade de Lisboa. Feel free to do a pull request to improve this FAQ.



---------------------------------------------------------------------------------------------------------------------------
### Thesis documentation

#### What documentation do I need to deliver and when?
There are two essential documents you are required to deliver during the first semester of your thesis.
1. **Acordo Especifico:** *Only for students at FCUL.* Depending if you have co-advisors or not, you can find the documents here: **Acordo Especifico S/ Coorientador** or **Acordo Especifico C/ Coorientador**. Should be delivered after two months of the starting date, e.g., if you put October 1st as starting date, should be delivered by 30th October. 
2. **Registo de tese:** [Available here](https://ciencias.ulisboa.pt/sites/default/files/fcul/unidservico/ua/documentacao/Impresso_registo_2ciclo.pdf). Should be delivered at maximum by 31st December.

A suggestion is to deliver this both documents simultaneously, as both require the signature of your advisor, by 30th November.

#### I no longer like my thesis title, can I change it?
Yes. Fill the following form, [Requerimento Geral](https://ciencias.ulisboa.pt/sites/default/files/fcul/unidservico/ua/documentacao/Requerimento_Geral_form.pdf), stating that you would like to change your MSc. thesis title to: "Brand New Approach That Solves P = NP". You also are required to submit a letter signed by your advisor accepting the change.

#### Do I need a Requirement to write my thesis in English?
You no longer need a requirement to write the thesis in English. However, you need to write a summary of your work in Portuguese.

#### Where do I submit the Preliminary Report?
Currently on [PEIpal](https://peipal.di.fc.ul.pt/) by the end of the second month since the starting date.

#### After a long journey, where do I submit my thesis?
First of, congratulations! The hardest part is already done. To submit your thesis follow the steps described in **Fenix >* Formação Avançada > Processos de Dissertação / Teses*. You will be provided a set of requirements that are required to be filled. 

**Warning:** You are asked to submit your resume (CV). The members of the jury take into consideration your curriculum, so spend some time improving it.

So far PEIpal is also being used, better be safe than sorry, also submit your thesis in it.

#### I have submitted my thesis, what now?
Now the Academic Services will check your application of the delivery of the thesis. Typically you will receive a notification on whether it as been accepted, or if further requirements or changes are needed. There were some cases were students were not notified, so we encourage you to daily visit the page. After being accepted, you are required to pay 100,00€ for the thesis submission and be able to present your thesis.

#### I have just defended my thesis on proving P = NP, what is the next step?
During the thesis discussion the jury may have delibered that you are required to make some changes to your thesis.
You will be provided a list or document with the changes, and you will have **seven** business days to correct your thesis and forward your corrections to your advisor. After the advisor accepts the changes, you will need to send it to gepg@fc.ul.pt.

You also are required to delivered a CD with the thesis and the CD cover to the academic services. You need to make an appointment by email or phone [(visit for more information)](https://ciencias.ulisboa.pt/pt/horarios-de-atendimento-covid).



---------------------------------------------------------------------------------------------------------------------------
### Thesis Template and formatting

The thesis must follow a set of rules presented [here](https://ciencias.ulisboa.pt/sites/default/files/fcul/unidservico/ua/documentacao/2ciclo/normas_escrita_trabalho_final.pdf) by the faculty.

#### What template should I use in my thesis?
There are two templates, in **LaTeX** and **Word**, available for the PEI students. We advise the use of the LaTeX template with [Overleaf](overleaf.com/) as it severaly improves thesis presentation. The LaTeX template, however, is currently outdated, and, until a pure soul decides to push an update, here are some corrections you need to do:

1. **Cover:** is completely wrong. You need to generate a pdf from the Word template cover, and use includepdf.
2. **Letter size** should be Times New Roman and set to 11 (*only enable when delivering*).

#### My references are not uniform, how do I deal with this?
A great suggestion is to use [dblp](https://dblp.org/) to search for the paper you need, and obtain the citation.

#### What is the difference between Background and Related Work, same chapter or different chapters?
Typically this is highly dependent of your work. The background presents the basis of the required information for the regular reader to understand your thesis. If your work, for instance, combines two completely different areas of Computer Science, perhaps two chapters may be a good solution. Another approach, is to mix both background and related work and 

#### Where should I save my thesis?
A great recommendation is to save your thesis on Git. It will allow you to control the modifications you do throughout the year. In your repository, include a make file to automatically compile your thesis. Don't forget to add the auxiliary files from latex to the [.gitignore](https://github.com/github/gitignore/blob/master/TeX.gitignore).



---------------------------------------------------------------------------------------------------------------------------
### Thesis Suggestions

This section presents some tips and tricks on how to improve your thesis to prevent your advisor from highlighting in red your thesis. You can find further tips provided by [Claire Le Goues when writting papers](https://clairelegoues.com/2016/08/23/things-i-keep-repeating-about-writing/)!

- Do not separate the subject and the predicate with a comma 
- Use prefixes in your label. For instance:  
   ```
    \label{chap:introduction} 
    \label{sec:motivation} 
    \label{fig:amazing_photo} 
    \label{code:amazing_code}
    ```
- This may depend on your advisor: create a `tex` file per chapter and use `\include` in the main latex file. 
- Disable the Times New Roman font until you deliver your thesis (*spare your eyes!*)
- When citing multiple articles always use `\cite{ref1, ref2, ref3}`.
- The last chapter of the introduction is the organization of the document. Do not include the Introduction in the document organization
- Each chapter should start with a small introduction. If your chapter includes different and complex components, a diagram might be interesting to include to describe the interaction between the sections.
- *Send us any extra tips!*




---------------------------------------------------------------------------------------------------------------------------
## Contributors
- [Alcides Fonseca](https://github.com/alcides)
- [Guilherme Espada](https://github.com/GUIpsp)
- [Catarina Gamboa](https://github.com/CatarinaGamboa)
- [João David](https://github.com/JoaoDavid)
- [Máximo Oliveira](https://github.com/MaximoOliveira)
- [Bernardo Ferrari](https://github.com/tarberd)

