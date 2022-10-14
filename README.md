# dbt-sandbox

Running
python3 -m pip install virtualenv

python3 -m virtualenv env

. env/bin/activate

pip install -r requirements.txt

streamlit run app.py

(optional) streamlit run pydeckapp.py --server.port=8081
(optional) streamlit run application.py --server.port=8082
(optional) port forward appropriate port through local VSCode

Port Forward Example
docker compose up

psql -U dbt drsat

\l
