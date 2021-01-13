# cdn_bank_viz
Streamlit app for visualizing stock data for canadian big 5 banks.

Prerequisites: have [Docker](https://www.docker.com/products/docker-desktop) installed

Instructions:

1. clone this repo: `git clone https://github.com/jon-tk-chan/cdn_bank_viz.git`
2. change working directory into repo folder: `cd cdn_bank_viz`
3. Build Docker image to run the app: `docker build -t cdn_bank_viz .`
    Note: remember to include the `.` at the end
4. Run Docker container, using port 8501: 'docker run -p 8501:8501 cdn_bank_viz'
5. In your browser, open the app using the given localhost port: `http://localhost:8501/`

## References

[Build 12 Data Science Apps in Python and Streamlit](https://www.youtube.com/watch?v=JwSS70SZdyM&list=PLPLSnr3ZK9T4uT6vmUxtEVL32XVpfV_9p&index=98&t=1516s)

