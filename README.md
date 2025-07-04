# Seismograms-Spectral-Transformation
This project analyses the 2023 Syria–Turkey Earthquake by downloading the seismic waveform data, plotting seismograms, and applying spectral transformations to visualise the frequency content of the ground motion. 
On 6th February 2023, the earthquake struck southern and central Turkey and northern and western Syria with a magnitude (Mw) of 7.8 and with a depth of 17.9km. The epicentre was located 37km west-southwest of Gazientep, a major city in south-central Turkey. The impact of the earthquake could be felt in four countries: Turkey, Syria, Lebanon and Israel. 

### Seismic Data Source 
#### The seismic waveform data is downloaded from IRIS using the following parameters: 
  Network: IU 
  Station: KONO
  Location: 00 
  Channel: BHZ 


### Workflow Summary 
1. Download waveform data using ObsPy 
2. Plot the raw seismogram
3. Filter the seismogram 
4. Apply Fast-Fourier Transform (FFT) to visualise the frequency domain 
