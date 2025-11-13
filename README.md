# Oil-spill-aws-sns-alerts
Oil Spill Detection Using U-Net & Streamlit This project implements a U-Net–based deep learning model to detect oil spills from SAR satellite imagery (Sentinel-1 & PALSAR). It also includes a Streamlit web app for visualizing predictions and estimating spill severity.

Project Structure oil-spill-detection-project/ │ ├── unet_model/ │ └── train_unet.py │ └── streamlit_app/ └── app.py How to Run the Streamlit App

pip install -r requirements.txt streamlit run streamlit_app/app.py Train the U-Net Model python unet_model/train_unet.py Model Features U-Net architecture for segmentation

Works with SAR images (Sentinel & PALSAR)

Generates binary spill masks

Severity estimation by area calculation

Streamlit UI for end-to-end visualization

Dataset The dataset used is the SOS SAR Oil Spill Dataset (CBDNet) containing:

Sentinel SAR images

PALSAR SAR images

Corresponding ground-truth masks

Dataset is not uploaded in this repo due to size. Download from the official source.
