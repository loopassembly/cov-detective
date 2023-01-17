
# Real-Time Data Visualization and Temperature Tracking with Django and Arduino: An Autonomous System with Face Detection



## Introduction

This project is an autonomous data visualizer and temperature tracker that uses an Arduino microcontroller to collect data and send it to a real-time database. The data is then displayed on a web interface created with Django. With the outbreak of the COVID-19 pandemic, it is more important than ever to ensure that everyone entering public spaces is healthy and symptom-free. This project has been designed to help with this task by adding a face detection feature that ensures that users are wearing masks.
## Acknowledgements

 - Arduino board
 - Temperature sensor
 - Webcam
 - Django
 - OpenCV


## Installation
- Install the necessary dependencies by running `pip install -r requirements.txt`
- Connect the temperature sensor to the Arduino board and upload the provided Arduino sketch to the board.
- Run the Django server by executing `python manage.py runserver`
- Access the web interface by navigating to `http://localhost:8000` in your web browser.
## Usage
    1. The temperature sensor will begin collecting data as soon as the Arduino sketch is uploaded.
    2. The data will be sent to the real-time database and displayed on the web interface.
    3. The face detection feature will activate when the user accesses the web interface. If a face is detected without a mask, a warning message will be displayed.
    4. The data can be visualized using the provided graphs and charts on the web interface.



## Troubleshooting
- If the temperature data is not being displayed on the web interface, check the connection between the Arduino board and the computer.
- If the face detection feature is not working, check that the webcam is properly connected and enabled.
## Video demonstration 


https://user-images.githubusercontent.com/62586139/212832864-9a6872fe-4f72-4a5f-ade9-55e30dffe9ea.mp4


## Tech Stack

**Client:** bootstrap

**Server:** Django , arduino/raspberry 


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://loopassembly.in/)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/loopassembly/)

[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/loopassembly)


## Conclusion

This project demonstrates the use of Arduino and Django to create an autonomous data visualization tool with real-time updates and face detection capabilities. It can be easily adapted and customized for different types of data collection and analysis. It is particularly useful during the COVID-19 pandemic as it can help to ensure that everyone entering public spaces is healthy and symptom-free.
## Support

For support, email loopassembly@gmail.com.


## License

[MIT](https://choosealicense.com/licenses/mit/)

