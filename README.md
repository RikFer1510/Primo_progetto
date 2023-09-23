# Primo_progetto
meme_dict = {
             "CRINGE":"Qualcosa di eccezionalmente strano oimbarazzante",
             "LOL":"Una risposta comune a qualcosa di divertente",
             "ROFL":"ROFL è utilizzato come reazione a qualcosa di divertente, similea LOL",
             "LMAO":"Simile a LOL, si usa per esprimere una cosa divertente e in inglese significa 'laughing my ass of' ovvero 'ridendo a crepapelle'",
             "OMG" : "Significa 'oh my god', ovvero 'oh mio dio'"
             }

parola = input("Scrivi una parola che non capisci (usa solo lettere maiuscole!): ")

if parola in meme_dict.keys():
  print(meme_dict[parola])
else:
  print("Non abbiamo ancora questa parola...Ma ci stiamo lavorando!")
      
