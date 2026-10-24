# AgroGuide AI — Starter Source Code

A responsive front-end prototype for a farming assistant aimed at farmers in Gombe State, Nigeria.

## Files
- `index.html` — page structure and interface
- `style.css` — responsive visual design
- `app.js` — language toggle, photo preview, and rule-based preliminary crop guidance

## Run it
1. Download and extract the ZIP.
2. Open `index.html` in Chrome, Edge, or Firefox.
3. Select English or Hausa, choose a crop and symptom, then click **Get preliminary guidance**.

No installation or server is required for this prototype.

## Important limitations
This is a front-end prototype. It does **not** yet include:
- a real AI model or image-based disease recognition;
- live weather data;
- verified, up-to-date crop market prices;
- a server, database, user accounts, or cloud storage.

The photo is only previewed locally in the browser; it is not sent anywhere. The symptom guidance is a simple demo ruleset and must not be treated as a confirmed diagnosis.

## Suggested next development steps
1. Add a Python FastAPI backend.
2. Integrate a tested crop-disease image model and evaluate it on locally relevant crops.
3. Connect a language model such as a supported Gemma model for Hausa/English Q&A.
4. Add a weather API and a reliable local market-data source.
5. Add privacy, security, consent, and offline/low-bandwidth support.
6. Test recommendations with agricultural extension officers before public deployment.

## Open-source license
This starter project is offered under the MIT License. You may adapt it, keep attribution, and share modifications.

MIT License

Copyright (c) 2026 AgroGuide AI contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
-AI-smart-assistance