# Simple Flask Web App

## 🧰 Framework Used

This project is built using the **Flask** micro web framework for Python. Flask was chosen due to its lightweight nature and ease of use for building quick web prototypes and small-scale applications.

- **Flask Version**: 2.x
- **Python Version**: 3.8+

## 🚀 How to Run the Project

1. **Clone the Repository**  

2. **Create a Virtual Environment (Optional but Recommended)**  

3. **Install Dependencies**  

4. **Run the App Locally**  

5. **View in Browser**  
Navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your web browser.

## 🛠️ Issues Encountered & Solutions

- **Issue**: *"ModuleNotFoundError: No module named 'flask'"*  
**Solution**: Flask was not installed in the environment. Running `pip install flask` fixed this.

- **Issue**: *App not auto-reloading when changes were made*  
**Solution**: Used `debug=True` in `app.run()` to enable development mode:
```python
app.run(debug=True)
