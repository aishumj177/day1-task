# lin1
## line2
### line3
#### line4
###### line5
# h1
## h2
### h3
#### h4
###### h5

*italic*
![alt text](image.png)

from googletrans import Translator

# Create translator object
translator = Translator()

# English text
text = "Hello, how are you?"

# Translate to Kannada (language code: 'kn')
translated = translator.translate(text, dest='kn')

# Print result
print("Original:", text)
print("Kannada:", translated.text)