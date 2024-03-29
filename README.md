
# Ticka Chatbot

What is Ticka : 
Ticka is an online platform that connects users with local artists, allowing them to create and purchase customized products with unique designs.
Website : https://ticka.world/

## Diagram

![Diagram](https://github.com/Fahdlabba/Ticka-Chatbot/blob/558b7fa48c0fb4b45d1eefcb2193296da1e2dd6a/Diagram.png)

## Tech Stack

**Tools:** Langchain , HuggingFace , BeautifulSoup 

**Vectore Store:** Faiss

**LLM:** Mistral 7B V2 

**Server:** FastAPI


## API Reference

#### Ask Questions

```http
  GET /ask/question
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `question` | `string` | **Required**.Your Question |




## Usage/Examples

```javascript
Request :/ask/Give me 2 hoodies products ?

Json Output :{"Answer ":" The hoodie products "
hoodie-roronoa-zoro-hoodie" and "hoodie-jujutsu-kaisen" 
are available with prices of "73.00. TND" each."}
```


## Authors

- [@Fahdlabba](https://github.com/Fahdlabba)


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Support

For support, email Labbafahd012@gmail.com.

