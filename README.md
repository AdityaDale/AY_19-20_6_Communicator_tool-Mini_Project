To compare trees first we have to generate tree,so the steps to generate sentence tree using natural language are given below.<br/>

Step 1: First convert hindi sentence into wx format.<br/>
Step 2: Then Parse wx formated hindi sentence by using irshad_parser.<br/>
Step 3: Generate tree from the output generated by irshad_parser i.e conll format.<br/>
Step 4: To generate the conll format of english parse it with Stanford_parser.<br/>
Step 5: Then Generate Tree from the resultant conll format.<br/>
Step 6: Then process of comparison of trees will be automatically done. 
