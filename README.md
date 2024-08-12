# Shoezap

Shoezap is an innovative web application that allows users to find the perfect shoe based on their prompts. Users can interact with the system using natural language through a chat interface powered by the Gemini API. Once a shoe is selected, users can virtually try it on in 2D using advanced machine learning models.

## Features

- Chat with Gemini API: Users can describe their ideal shoe, and the system will recommend options based on their prompts.
- 2D Virtual Try-On: After selecting a shoe, users can see how it would look on their feet in a 2D environment.
- Fantastic UI: Shoezap features a modern, user-friendly interface that enhances the shopping experience.
- Background Removal: Clean and professional product images with backgrounds automatically removed.
- Real-time Object Detection: YOLOv8 is used for accurate and efficient shoe detection and virtual try-on placement.

## Technology Stack

- Backend:
  - Flask: A lightweight Python web framework used to build the backend API for the application.
  - Gemini API: Powers the chat functionality, enabling natural language processing and shoe recommendations.

- Frontend:
  - HTML/CSS/JavaScript: For building the interactive and responsive user interface.
  
- Machine Learning Models:
  - YOLOv8: Used for shoe detection and positioning in the virtual try-on feature.
  - Background Remover: Removes the background from shoe images for a cleaner visual presentation.
  - Text2Image: Generates images of shoes based on user prompts, creating a visual representation of the description provided.

## Installation

### Prerequisites

- Python 3.x
- Flask
- YOLOv8
- Node.js and npm (for managing frontend dependencies)
- A virtual environment (recommended)

### Steps to Install

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/shoezap.git
   cd shoezap
2. *Create and activate a virtual environment:*:
   ``` bash
     python -m venv venv
     source venv/bin/activate  # On Windows, use venv\Scripts\activate
3. Install backend dependencies:::
   ```bash
    pip install -r requirements.txt
4. *GO TO /flask_clone/Gemini-Bot DIRECTORY :*
```bash
   cd flask_clone
   cd Gemini-Bot

```
## Download `best.pt` File
###and kindly edit code in all py files and js based on the correct file path

You can download the `best.pt` file from the following link and store in gemini-bot file:

[Download best.pt](https://drive.google.com/file/d/10bGUTIv01ES-RzUPWLUPV9KmCjf9M0E1/view?usp=sharing)
  
       
5. **Run web app **:
    ```bash
      python app.py

## Usage

### Open the application:
Navigate to the URL where the Flask server is running (e.g., [http://127.0.0.1:8080/](http://127.0.0.1:8080/)).

### Chat with the Gemini API:
1. Enter a description of your ideal shoe in the chat interface.
2. The system will suggest shoes based on your input.

### Virtual Try-On:
1. Select a shoe from the recommendations.
2. Use the virtual try-on feature to see how the shoe looks in 2D on your feet.

## Models Used
- YOLOv8: For detecting the shoe in images and accurately placing it on the user's foot in the virtual try-on.
- Background Remover: Removes unnecessary background from shoe images to provide a clean visual.
- Text2Image: Converts text descriptions into shoe images, helping users visualize their desired shoes.


## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
- YOLOv8 for providing the object detection framework.
- Flask for the web framework.
- Gemini API for powering the chat functionality.

### Collaborators

- **[PriyaDharshini22-2005](https://github.com/PriyaDharshini22-2005)**
- **[Devakesavan](https://github.com/Devakesavan)**
- **[Dhatchayani2006](https://github.com/Dhatchayani2006)**
- **[karthikeyan261222](https://github.com/karthikeyan261222)**
## Contact

For any inquiries, please contact us at [byteknightsbk24@gmail.com](mailto:byteknightsbk24@gmail.com)
