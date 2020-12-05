import sys

 

x = input("Input your Statement of Jurisdiction.")

#Type sample input: This action arises under 42 U.S.C. §1983; under the due process rights provided by the First and Fourteenth Amendments to the United States Constitution

 

keywords = ["due process", "equal protection", "extra mozzarella","SS-396 chevelle"]

 

for z in keywords:

 	if z in x:

      	break

 	

else:

 	

 	sys.exit("It seems you may not have a question of federal or Constitutional law.")

 

print("Got it. A federal question.")

print(z)

 

if z == "extra mozzarella":

 	yum = input("State-run cafeteria? Deep dish and calzones on menu?")

elif z == "SS-396 chevelle":

 	vroom = input("What year? All years were great, just curious.")

 

#def order_text(func_PACER_pdf_ocr_cellpic2text):

#	if decode_arg(func_PACER_pdf_ocr_cellpic2text) == 1:

 #      	#return(fetch_pacer(func_PACER_pdf_ocr_cellpic2text))

#

 

#ord = order_text("0:20-cv-01199-DWF-DTS, DOCUMENT 16")

 

     ord="Order does not mention the basis of jurisdiction."#test case

 

if z in ord:

 	print("The order mentioned the basis of jurisdiction. First test passed.")

 	

else:

 	

 	sys.exit("The order did not mention the basis of jurisdiction. Refer to Senate judiciary subcommittee on impeachment for further analysis.")