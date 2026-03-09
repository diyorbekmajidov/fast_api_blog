uv init fast_api_blog #create project
uv add "fastapi[standard]"  # add dependencies 
uv run fastapi dev main.py # run the project

uv add sqlalchemy # add sqlalchemy dependency
python3 -c "import secrets; print(secrets.token_hex(32))" # generate secret key for JWT