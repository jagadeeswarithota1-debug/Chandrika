
basic_chatbot():
    print("Chatbot: Hello! Type 'bye' to exit.")
    
    while True:
        # Get input from user and convert to lowercase for easier matching
        user_input = input("You: ").lower()
        
        # Rule-based logic using if-elif-else
        if "hello" in user_input : 
            print("Chatbot: Hi!")
            
        elif "how are you" in user_input:
            print("Chatbot: I'm fine")
            
        elif "bye" in user_input:
            print("Chatbot: Goodbye!")
            break  # Exit the loop
            
        else:
            print("Chatbot: I'm not understanding")

# Run the function
if __name__ == "__main__":
    basic_chatbot()
    
