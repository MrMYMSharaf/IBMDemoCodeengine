# IBMDemoCodeengine

docker build -t streamlit-app . 
docker run --name streamlit-container -p 8501:8501 -d -v ${pwd}:/code streamlit-app
