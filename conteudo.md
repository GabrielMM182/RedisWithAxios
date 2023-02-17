## funcionar import from 

Update For Node.js / NPM
Add "type": "module" to your package.json file.

{
  // ...
  "type": "module",
  // ...
}

-> npm i ioredis (redis especificamente para js)

->  digitar no cli sua api key 
export WEATHER_API_KEY=<...>

## deve rodar o docker junto para funcionar

-> docker run --name redis-cache-axios -p 6379:6379 -d redis