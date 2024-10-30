# LAKSHITHA-MD
MY FIRST OWN BOT
<div align="center">
	<h3>🍁LAKSHITHA-MD🍁</h3>
<img src="https://i.ibb.co/zQg9dzm/IMG-20241025-WA0018.jpg" width="300" height="190">
</div>

<h3>🍁 How To Deploy </h3>

<h5>🍁 First tap to Fork button and create new fork</h5>

<hr>
	
<h3>🍁 Get Your SESSION ID 👇</h3> 
<h5>🍁 SESSION_ID Error Fixed ✅</h5>
	
<button><tr><a href="https://pair-web-public.koyeb.app/">🌸 SESSION_ID</a></tr></button>

<h5>🍁 Now get your inbox and copy sessino id</h5>
<h5>🍁 If you past session id in (config.js/SESSION_ID || "past_copy_text")</h5>


<h5>🍁 Deploy Free Workflows 👇</h5>

```
name: Node.js CI

on:
  push:
    branches:
      - main
  pull_request:
    branches:
      - main

jobs:
  build:

    runs-on: ubuntu-latest

    strategy:
      matrix:
        node-version: [20.x]

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Set up Node.js
      uses: actions/setup-node@v3
      with:
        node-version: ${{ matrix.node-version }}

    - name: Install dependencies
      run: npm install

    - name: Start application
      run: npm start
```


<div align="center">

