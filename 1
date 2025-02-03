import random
import requests

def get_weather(city):
    API_KEY = "your_api_key_here"  # Replace with a real API key
    url = f"http://api.openweathermap.org/data/2.5/weather?q={city}&appid={API_KEY}&units=metric"
    response = requests.get(url)
    data = response.json()
    if data.get("main"):
        temp = data["main"]["temp"]
        return f"The current temperature in {city} is {temp}°C."
    else:
        return "Sorry, I couldn't fetch the weather for that location."

def chatbot_response(user_input):
    responses = {
        "hello": "Hi there! How can I assist you today?",
        "how are you": "I'm just a bot, but I'm doing great! How about you?",
        "your name": "I'm ChatBot, your virtual assistant!",
        "bye": "Goodbye! Have a great day!",
    }
    
    user_input = user_input.lower()
    if user_input in responses:
        return responses[user_input]
    elif "weather" in user_input:
        city = user_input.split("weather in ")[-1]
        return get_weather(city)
    else:
        return "I'm not sure how to respond to that, but I'm learning every day!"

def main():
    print("Hello! I'm a simple chatbot. Type 'bye' to exit.")
    while True:
        user_input = input("You: ")
        if user_input.lower() == "bye":
            print("ChatBot: Goodbye!")
            break
        response = chatbot_response(user_input)
        print(f"ChatBot: {response}")

if __name__ == "__main__":
    main()
