# Babel System 

Multiplatform API with access to Gemini models. ✨

## Information ℹ️

[Creator](https://github.com/Eloazy) 👨‍💻

[DC Server](https://discord.gg/3Fzhj6ed9C) 💬

This API is an initiative and built by just one developer being for private and non-profit use. ❤️

> [!NOTE]
> The babel system is not available due to API limitations, only in future updates will it be allowed for use 🚧

## API branches 🌳

| Branch | Description | Version |
|--------|-------------|---------|
| Babelite 🌐 | Server/Site | LTS: 2.0.2-D |
| BabelCord 💬 | Discord Branch | LTS: 4.0.1 |
| Baberome 🌍 | Chrome Branch | LTS: 1.0.0 |
| Cardial ❤️ | Discord Branch (to RPG games) | LTS: 1.0.0 : Discontinued 🛑 |
| Babelever ❌ | Server | 1.0.0 : Discontinued 🛑 |

## Access to source code 🔓

Access to the source code is free for anyone, except for Babelite and Babelcord, as it still contains the API key in its history, while the API key is exposed, access will be private only to developers. 🔑

# Documentation 📚

## Models 🧠

| Model | Status | max output |
|--------|-------|------------|
| gemini-2.0-flash-exp.js | Global ✅ | 8192 tokens |
| gemini-2.0-flash-thinking-exp-01-21.js | Global ✅ | 2000 tokens |
| learnlm-1.5-pro-experimental.js | Global ✅ | 2000 tokens |

## Limitations ⚠️

Its use is local only: Babelite host in `PORT: 1025` 🏠

> [!WARNING]
> Baberome only suported by babelite ^3.0.1 📏

Discord Branchs (Cardial and BabelCord) 💬

> [!WARNING]
> Have limits of 2000 characters, returning an error if this limit is exceeded 📏

## Connection 🔗

Done by `POST` method accessing `localhost on port 1025`
Receiving and sending only information in `application/json`

May return the response in `result` or `result.result` depending on the method of submission

*Usually returns in `result`*

## Key instructions 🔑

The API uses its own key, in the future a new branch will probably be created for public use where the use of a private key will be required. 🗝️

## Integrated Commands ⚙️

The API uses integrated commands:

| Command | Usage |
|--------|-------|
| `$status` | Send information about the current API 📊 |
| `$model [number]` | Exchange the current model for another model in list, the input must be by the list number 🔄 |
| `$modelList` | List all Models Avaliable 📜 |
| `$clean` | Clean the Model memory 🧹 |
| `$temp` | Change the `temperature` of model (0 to 1) 🌡️ |
| `$top` | change the `top_p` of model (0 to 2)  ⬆️ |

- For Discord: `/babelaife $[command]`
- For Babelite: `$[command]`

### Temperature and top_p 🔥

temperature and top_p are the fine controls of the API, with temperature being the generation engine and top_p being the selection filter, which can be random or precise 🎛️

They are limited to
- temperature >= 0 and <= 1 🌡️
- top_p >= 0 and <= 2 ⬆️

### Manipulation of fine motors 🕹️

To manipulate fine engines, this command must be carried out, either in the discord model or on its main website using the period instead of the comma for decimal numbers.

example: `$top 1.5` | result: top_p changed to 1.5 ✅

## Errors ❌

Server: 🖥️
- Error `500` | Internal error from GEMINI 💥
- Error `400` | Bad Request, Error on JSON scope 📝
- Error `401` | Authentication error, missing or invalid key 🔑

Discord: 💬

**All errors from server and:**
- Error `50035` | Invalid Form > BASE_TYPE_MAX_LENGTH 📝

# API acquisition 🛒

It can be requested in two ways, one being purchased and the other from Gemini's free models. For this you must access the Gemini side and create a key 🔑

> [!NOTE]
> The use of personalized keys is not yet available to the public, being for private use only as mentioned with access restricted to developers only.

# Development 🛠️

Update views on the code can be seen [clicking here](https://github.com/users/Eloazy/projects/3) 👀

Feedbacks and Ideas can be uploaded in discord server [clicking here](https://discord.gg/3Fzhj6ed9C) 💡

> [!TIP]
> To participate in the project you must contact the project leader through the same [discord server](https://discord.gg/3Fzhj6ed9C) 🤝

> The entire application was created by just one person and with a lot of love and dream of having its own integrated system
> ❤️ From the developer, with love ❤️
