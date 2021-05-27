**Activate the virtual environment**
```
C:\Users\Arpit Garg\Envs\blockchain-env\Scripts>activate
```

**Install all packages**
```
pip3 install -r requirements.txt
```

**Run the tests**
Make sure to activate the virtual environment
```
python -m pytest backend/tests
```

**Run the application and API**
Make sure to activate the virtual environment
```
python -m backend.app
```

**Run PEER**
Make sure to activate the virtual environment and have internet connection
```
set "PEER=True" && python -m backend.app
```

***Run the frontend***
In the frontend directory:
```
npm run start
```

***Seed the backend with data***
Make sure to activate the virtual environment.
```
set "SEED_DATA=True" && python -m backend.app
```