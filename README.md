# oreally
a chatbot that asks you what you really think about things for real

## Motivation

people are isolated and constantly bombarded with propaganda that promotes cruelty and glorifies violence in all its forms. what's missing is self-reflection and nothing addresses that better than a conversation. however the opportunities to talk to eachother and collectively reflect are few and far between. Enter Oreally , it's a chat bot that doesnt talk at you but instead asks you questions about what you think about things and keeps asking questions until you find your own answer as to why you might think what you think and if you really think what you say you think and why. then it provides candidate voting records and election information in a easily digestable and accessible form to the user.


## Install and Run

### Prerequisites

Ensure you have Poetry installed. If you don't have Poetry installed, you can install it using the following command:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

Or using `pipx`:

```bash
pipx install poetry
```

### Setting Up the Project

1. **Clone the Repository**:

   First, clone the repository to your local machine:

   ```bash
   git clone https://github.com/Josephrp/oreally.git
   cd oreally
   ```

2. **Install Dependencies**:

   Install the project dependencies using Poetry:

   ```bash
   poetry install
   ```

3. **Activate the Virtual Environment**:

   Poetry automatically creates a virtual environment for your project. Activate this environment using:

   ```bash
   poetry shell
   ```

### Running `main.py`

Once the virtual environment is activated, you can run `main.py` using the Python interpreter managed by Poetry:

```bash
poetry run python main.py
```

