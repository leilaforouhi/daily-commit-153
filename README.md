def get_unique_words(text):
    words = text.lower().split()
    return sorted(set(words))


if __name__ == "__main__":
    sentence = "Python coding with daily GitHub coding practice"

    print(f"Sentence: {sentence}")
    print(f"Unique words: {get_unique_words(sentence)}")
