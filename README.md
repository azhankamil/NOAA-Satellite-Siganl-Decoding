## NOAA-Satellite-Siganl-Decoding



Decoding signals from NOAA Satellites using Python and receiving the signal using a V-dipole antenna and RTL-SDR is an exciting project that enables amateur radio enthusiasts and weather enthusiasts to gather and process weather satellite imagery.

NOAA (National Oceanic and Atmospheric Administration) operates a series of weather satellites known as NOAA Satellites. These satellites capture high-resolution images of Earth's atmosphere and surface, which are used to monitor weather conditions, track storms, and aid in climate research. NOAA Satellites transmit these images and other meteorological data down to Earth via radio frequency signals.

To receive and decode these signals, you'll need a few components:

V-Dipole Antenna: A V-dipole antenna is a simple and inexpensive design that can be built at home. It is known for its good performance in receiving satellite signals.

# V-Dipole Antenna

<img width="863" alt="Screenshot 2023-07-25 at 1 53 44 AM" src="https://github.com/azhankamil/NOAA-Satellite-Siganl-Decoding/assets/79698742/b57bb7c5-de55-4f1e-be68-8df9fa54fbd9">



Most Important Antenna Orientation for Signal Reception in <https://github.com/azhankamil/NOAA-Satellite-Siganl-Decoding/blob/main/README.md#fig-antenna-orientation>

# Fig (Antenna Orientation)
<img width="857" alt="Screenshot 2023-07-25 at 1 55 05 AM" src="https://github.com/azhankamil/NOAA-Satellite-Siganl-Decoding/assets/79698742/29ab8cb7-70e6-44e3-b104-eb8b400d3a1d">




RTL-SDR Dongle: An RTL-SDR (Software-Defined Radio) dongle is a low-cost radio receiver that connects to a computer via USB. It can tune to a wide range of frequencies and is commonly used for receiving various radio signals, including NOAA satellite signals.

# RTL-SDR Dongle
<img width="849" alt="Screenshot 2023-07-25 at 1 55 43 AM" src="https://github.com/azhankamil/NOAA-Satellite-Siganl-Decoding/assets/79698742/befc5da5-55a1-457e-aabe-1d3bb3572d4d">




Computer with Python: You'll need a computer with Python installed, as well as some Python libraries, to process and decode the received signals.

The process of decoding NOAA satellite signals involves the following steps:

Set Up the Hardware: Assemble the V-dipole antenna and connect it to the RTL-SDR dongle. Position the antenna in an open area with a clear view of the sky.

Install Dependencies: Install the required Python libraries, such as rtl-sdr, numpy, and matplotlib, which are commonly used to work with RTL-SDR data.

Tune and Capture the Signal: Use Python to interface with the RTL-SDR dongle and tune it to the correct frequency for the NOAA satellite you want to receive. The frequencies of NOAA satellites vary depending on the specific satellite in operation.

Record the Signal Using SDR Software (Ex- Cubic SDR, SDR Sharp): Capture the radio frequency signal transmitted by the NOAA satellite and save it as a raw data file.
# Signal Recording
<img width="984" alt="Screenshot 2023-07-25 at 1 59 12 AM" src="https://github.com/azhankamil/NOAA-Satellite-Siganl-Decoding/assets/79698742/8467ab60-b325-4f13-a684-a8171f2fd886">

Decode the Signal: Convert the recorded raw data into a meaningful image using decoding software. One popular software for this purpose is the "WXtoImg" software, which can process the audio signals and produce weather satellite images in various formats.

Visualize the Image: Use Python and libraries like numpy and matplotlib to visualize and enhance the decoded weather satellite image.

This project offers a great learning experience in radio frequency communication, signal processing, and image decoding. It allows hobbyists and weather enthusiasts to access real-time weather data captured by NOAA satellites without the need for expensive equipment. Keep in mind that receiving signals from satellites can be influenced by various factors, including antenna positioning, atmospheric conditions, and interference, so experimentation and fine-tuning may be required to achieve optimal results.



##
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://azhankamil.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/azhan-kamil-4128b31a7/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/azhankamil)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:gj8915@myamu.ac.in)
