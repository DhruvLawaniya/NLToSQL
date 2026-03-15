# NLToSQL
A Natural Language to SQL generator


This project aims to :
1) Help provide a baseline for model output comparison- by insepecting the outputs rather than just judging them by accuracy.
2) Develop solutions to acheive NL->SQL with as little computational problem as possible
3) Demonstrate how this is an incredibly tideous task which can be challenging even for transformers.


Description:
Have you ever generated SQL using an LLM? If the SQL to be generated is even a little complex- the variation of outputs might differ a lot- even if all of them are correct. This poses a challenge for researchers aiming to develop solutions. 
SQL inherently follows little structure - considering different variable names, case insensitivity, no requisite for order. A lot of un-finetuned LLMs would also struggle to provide the same output everytime. 

This project is to see and analyze how different models[Feedforward,LSTM, LSTM with attention, Transforerms and LLMS] would yield different outputs given different inputs. 
I am preparing a website to visualise this process better- however I'll have some of the models in their respective repositories, to give an idea!

I have used the ATIS dataset to train these particular models. 

Any suggestions are welcome on my mail id: dhruvlawaniya2510@gmail.com
