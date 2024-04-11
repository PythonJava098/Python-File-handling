def elementCount(data):
    freq = {}
    for element in data:
        if element not in freq:
            freq[element] = 1
        else:
            freq[element] += 1

    return freq





def vowel(fileName):
    file_data = fileName.readlines()
    string = str(file_data)
    data = []
    count = 0
    
    for letter in string:
        if letter.lower() in "aeiou":
            data.append(letter)
            count += 1
            
    freq = elementCount(data)
    freq["Total"] = count
    
    return freq

def dictPresent(data):
    for letter in data.keys():
        freq = data[letter]
        print(letter, ":", freq)
        print("--------------------------------------------------")


def vowelFreq(fileName):
    dict_of_vowel = vowel(fileName)
    dictPresent(dict_of_vowel)


file_object = open("D:/Documents/Python/File Handling/file1.txt","+r")
print(vowelFreq(file_object))

    
        
            
