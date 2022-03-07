{"intents": [
	{"tag": "greeting",
	 "patterns": ["Hi", "Hi, How are you", "Is anyone there?","Hello"],
	 "responses" : [" Hello,Good to see you again", "Hello,How can I help you?"],
	 "context_set": ""
	 },
	{"tag": "age",
	 "patterns": ["How old", "What is your age?", "how old are you?", "age?"],
	 "responses" : ["I am 18 years old", "18 years"],
	 "context_set":""
	 },
	{"tag": "name",
	 "patterns": ["What is your name?", "What should I call you?"],
	 "responses": ["My name is Gina", "You can call me Gina"],
	 "context_set": ""
	 },
	{"tag": "shop",
	 "patterns": ["I would like to buy something", "I would like to purchase a product", "Can you recommend me something to buy?"],
	 "responses": ["Wiould you like to purchase men or women clothing?", "Whare the categories you are looking for?"],
	 "context_set": ""
	 },
	{"tag": "type",
	 "patterns":["I would like to look for women clothing", "I would like to purchase women clothing", "Women Clothing", "Men Clothing", "I would like to buy from mens section","I would like to purchase from womens section"],
	 "responses": ["Yes, we have a lot of options available. Please select from the folowing", "Yes, Sure"],
	 },
	{"tag": "colour",
	 "patterns": [" What are the colours available for the dress?", "What other colours are present for this shirt?"],
	 "responses": ["We have green, blue, white, yellow, black and red colours available", "Green, blue, yellow, white, black amd red"],
	 "context_set": ""
	 },
	{"tag": "size",
	 "patterns": ["What are the sizes available?", "I have sizes issues, can I get anoter size?"],
	 "responses":["Yes, we have S,M,L,XL sizes available. Please Select the one best suitable for you"],
	 "context_set": ""
	 },
	{"tag": "good bye",
	 "patterns": ["Goodbye", "Thank you, I am leaving"],
	 "responses": ["Have a good day", "Talk to you later"],
	 "context_set": ""
	 }
	]
 }
