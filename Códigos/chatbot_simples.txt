

openai.api_key = "xxx"


completion = openai.ChatCompletion.create(model="gpt-3.5-turbo", messages=[{"role": "user", "content": "Me dê 3 ideias de aplicativos que eu posso criar com IA GE TAVARES"}])
print(completion.choices[0].message.content)