# Spoken English to Written English

A python module to convert Spoken english to Written English

Ex : "two dollars" should be converted to $2. Abbreviations spoken as "C M" or "Triple A" should be written as "CM" and "AAA" respectively.

Note : This module is tested on Linux Machine


## Install

python3 setup.py install


## Usage

 >>python3 <br>
 >>from Converter import sp2wr <br>
 >>sp2wr.convert_sp_to_wr()<br>

'''
 >
 > [IN]:Enter Your paragraph of spoken english:
 
 >Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 A M. I always come home after 7 P M. I earn hundred 		dollars per day. My contact number contains double 5, quadruple 8, single 9 and triple 4. Recently, My weight got double 	 the weight of my friend whom I call C M. 
 
> [OUT]:The input Spoken English Paragraph: 
 
 >" Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 A M. I always come home after 7 P M. I earn hundred 	  dollars per day. My contact number contains double 5, quadruple 8, single 9 and triple 4. Recently, My weight got double    	       the weight of my friend whom I call C M. "
 	
  >Converted Written English Paragraph: 
  
 > " Hi! My name is Bruce. I am a Programmer. I try to wake up before 6 AM. I always come home after 7 PM. I earn $100 per 	    day. My contact number contains 55, 8888, 9 and 444. Recently, My weight got double the weight of my friend whom I call CM. "

>
'''