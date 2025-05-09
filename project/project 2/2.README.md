Here’s a sample README for your project:

---

# Voice Command System with Speech Recognition

## Overview

This project is a Voice Command System built using Python. It listens for specific voice commands, processes them using speech recognition, and takes corresponding actions (such as opening applications, playing YouTube videos, or reading the current time). The system also evaluates its performance using metrics like Word Error Rate (WER) and accuracy, and provides visualizations of the command success rates, frequency of commands, and success/failure trends.

## Features

* **Voice Command Recognition**: Uses speech recognition to listen and respond to specific voice commands.
* **Actions**:

  * Open Chrome browser
  * Open YouTube
  * Report current time
  * Play a YouTube video based on voice input
* **Performance Evaluation**: Measures the performance of the system using WER and accuracy.
* **Visualizations**: Displays:

  * Success/failure rate of the commands
  * Frequency of commands used
  * Success/fail trends over multiple attempts

## Technologies Used

* Python 3.x
* Libraries:

  * `speech_recognition`: For recognizing and processing speech commands
  * `pywhatkit`: For playing YouTube videos
  * `pyttsx3`: For text-to-speech functionality
  * `matplotlib`: For visualizations of results
  * `jiwer`: For calculating Word Error Rate (WER)
  * `sklearn`: For calculating accuracy score
  * `fuzzywuzzy`: For command fuzzy matching
  * `subprocess`: For opening applications like Chrome

## Setup Instructions

### Prerequisites

Make sure you have the following libraries installed:

```bash
pip install SpeechRecognition pyttsx3 pywhatkit matplotlib jiwer fuzzywuzzy
```

### Running the Code

1. Clone or download the repository to your local machine.
2. Ensure you have a microphone connected to your computer.
3. Run the script using the following command:

```bash
python voice_command_system.py
```

4. The system will prompt you to speak commands. It will listen three times and then evaluate the results.

### Example Commands

* "Open Chrome"
* "Open YouTube"
* "What is the time?"
* "Play \[YouTube video name]"

## Evaluation Metrics

* **Word Error Rate (WER)**: Measures how accurately the system recognized the speech input compared to the expected commands.
* **Accuracy**: Measures how many commands were recognized correctly.

## Visualizations

* **Command Success Rate**: A pie chart showing the percentage of successful and failed commands.
* **Command Frequency**: A bar chart displaying the frequency of each command used.
* **Success/Failure Trend**: A line plot showing the success or failure of the system over multiple attempts.

## Example Output

After the system has processed the commands, you will see:

```
----- Evaluation Metrics -----
Word Error Rate (WER): 0.15
Accuracy: 85.00%
```

Additionally, visualizations for command success rates, frequency of commands, and success/fail trends will be displayed as plots.

## Troubleshooting

* **Microphone Issues**: Ensure that the microphone is properly set up and accessible to the script.
* **Library Issues**: Make sure all required libraries are installed. If any library is missing, install it using pip.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Let me know if you'd like any changes!
