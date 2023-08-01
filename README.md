# Django OpenCV Backend

This project is a Django-based web application that uses OpenCV for image processing. It allows users to upload images and apply different filters to them.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed Python 3.6 or later.
- You have installed Django.
- You have installed OpenCV.
- You have a basic understanding of Django and OpenCV.

## Setting Up the Project

Follow these steps to set up the project:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/eugenefauntleroy/django_opencv_backend.git
```

2. Navigate to the project directory:

```bash
cd django_opencv_backend
```

3. Install the required Python packages:

```bash
pip install -r requirements.txt
```

4. Run the Django migrations:

```bash
python manage.py migrate
```

5. Start the Django development server:

```bash
python manage.py runserver
```

The application will be available at `http://localhost:8000`.

## Using the Application

To use the application, follow these steps:

1. Open a web browser and navigate to `http://localhost:8000`.
2. Click on the "Upload New" button to upload an image.
3. Select an image from your computer and click "Open".
4. Select a filter from the dropdown menu and click "Apply".
5. The filtered image will be displayed on the page.

## Practical Use Cases

This project has a wide range of practical applications, including:

1. **Image Editing Platform**: The project can be expanded into a full-fledged online image editing platform. Users could use it to apply filters and make other modifications to their images without needing to install any software.

2. **Educational Tool**: The project could be used as an educational tool for teaching concepts related to image processing and computer vision.

3. **Preprocessing for Machine Learning**: This project could serve as a front-end for preprocessing tasks in machine learning, particularly in computer vision tasks.

## Contributing to the Project

To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

## Contact

If you want to contact the project owner, you can reach Eugene Fauntleroy at `iwata.mich@gmail.com`.
