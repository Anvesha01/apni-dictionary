# apni-dictionary
print("Which name meaning you want to know from below options-")
print("[Omkar, Usha, Anvesha, Akash, Nikita, Ishika, Neelaksh, Jyoti, Muskan, Prachi]")
dictionary={"omkar":"The Supreme Energy that Governs the Universe","usha":"Raising of sun","anvesha":"Curious,kind","akash":"sky","nikita":"Goddess of home","ishika":"daughter of god","neelaksh":"blue-eyed","jyoti":"light","muskan":"Smile","prachi":"The first rays of the sun, the redness of the sun"}
word=input()
print(dictionary.get(word.lower()))
