# Fix My Code Challenge #1

## Description

This project involves fixing and improving an existing codebase across several tasks. Each task requires fixing specific issues or adding new features to existing codebases. The tasks cover a range of technologies including Flask, Python OOP, Rails, and React.

## Project Structure

| Task | Description | Source Code |
|------|-------------|-------------|
| **0** | **Server Status**: Debug and fix a Flask route for API status. | [status_server](./status_server/) |
| **1** | **My Square**: Resolve issues with a Python class representing a geometric square. | [square.py](./square.py) |
| **2** | **User Model**: Troubleshoot and enhance an OOP Python project with user modeling. | [user.py](./user.py) |
| **3** | **Blog Access**: Fix access issues and add features to a Rails blog application. | [blog](./blog) |
| **4** | **Never Leave the Office**: Address website issues and fix pagination in a React blog application. | [react-blog](./react-blog) |

## Learning Objectives

- Debug and fix issues in a Flask API endpoint.
- Identify and correct problems in a Python geometric class.
- Resolve issues in an object-oriented Python project.
- Fix and enhance a Rails blog application, including adding new features.
- Address issues in a React application and implement pagination.

## Requirements

- **Compiling Environment**: Ubuntu 14.04 LTS
- **File Requirements**: All files should end with a new line.

## How to Use

0. **Server Status**: Debug and fix a Flask route for API status.
1. **My Square**: Resolve issues with a Python class representing a geometric square.
2. **User Model**: Troubleshoot and enhance an OOP Python project with user modeling.
3. **Blog Access**: Fix access issues and add features to a Rails blog application.
4. **Never Leave the Office**: Address website issues and improve pagination functionality in a React blog application.

**Setup for Flask (Task 0):**
   - Install Flask:
     ```bash
     pip install flask
     ```
   - Run the Flask application:
     ```bash
     python -m api.v1.app
     ```

**Setup for Python OOP (Tasks 1 and 2):**
   - Ensure you have Python 3 installed:
     ```bash
     python3 --version
     ```
   - Install any required packages if specified in the files.

**Setup for Rails (Task 3):**
   - Ensure you have Rails installed:
     ```bash
     gem install rails
     ```
   - Run the Rails server:
     ```bash
     rails server
     ```

**Setup for React (Task 4):**
   - Ensure you have Node.js and npm installed:
     ```bash
     node -v
     npm -v
     ```
   - Install project dependencies:
     ```bash
     npm install
     ```
   - Run the React application:
     ```bash
     npm start
     ```

### Task 0: Fix the Flask API endpoint that returns the server status.

**Steps:**
- The issue might be with the route definition or the response. Ensure that the `/api/v1/status` route is correctly defined in your Flask application and returns a proper JSON response.

1. **Locate the File:**
   - **Directory:** `0x01-Fix_My_Code_Challenge/tree/master/status_server/api`

2. **Fix the Code:**
   - **Issue:** The `/api/v1/status` route returns a 404 error
   - **Potential Causes:**
     - The route might not be defined in the `app_views` blueprint.
     - The blueprint might not be registered correctly in `app.py`.
     - The file structure or import paths might be incorrect.
     - The `__init__.py` in the `api/v1` directory might be misconfigured.

3. **Steps to Fix:**
   1. **Check Blueprint Definition:**
      - Ensure the `app_views` blueprint is defined with the `/api/v1/status` route in the `status_server/` directory.

   2. **Verify Blueprint Registration:**
      - Ensure that `views` is registered in your `app.py`:

   3. **Verify File Structure:**
      - Ensure the project structure matches the import paths:

   4. **Check `__init__.py`:**
      - Verify `__init__.py` in `api/v1` is properly setting up the blueprint.

   5. **Run the Application:**
      - Start the application and test the endpoint:

      ```bash
      python app.py
      ```

      - Test the API with:

      ```bash
      curl -X GET http://0.0.0.0:5000/api/v1/status
      ```


### Task 1: Debug and correct issues in the `square.py` file.
- A Python class representing a square has some issues that need to be resolved to ensure proper functionality.
**Steps:**

1. **Locate the File:**
   - Directory: `0x01-Fix_My_Code_Challenge/blob/master/square.py`

2. **Fix the Code:**
   - Identify and correct the errors related to the geometric calculations or class implementation.

### Task 2: Debug and correct issues in the `user.py` file related to object-oriented programming.
   - The User model in a Python OOP project is malfunctioning. Fix the issues to ensure it operates correctly.
**Steps:**

1. **Locate the File:**
   - Directory: `0x01-Fix_My_Code_Challenge/blob/master/user.py`

2. **Fix the Code:**
   - Identify and correct errors in class methods or attributes.


### Task 3: Fix access issues in the Rails blog and add a new feature to manage post visibility.
- A Rails blog application has issues with accessing blog posts. Additionally, add a boolean `online` attribute to the `Post` model with a default value of `true`, and update the `Post#edit` route to allow toggling this attribute.
**Steps:**

1. **Locate the File:**
   - Directory: `0x01-Fix_My_Code_Challenge/tree/master/blog`

2. **Fix the Code and Add Feature:**
   - Fix access control issues and implement a boolean `online` attribute for `Post`.

### Task 4: Fix issues in the React application and implement pagination.
- Address website issues and fix pagination in a React blog application.
**Steps:**

1. **Locate the File:**
   - Directory: `0x01-Fix_My_Code_Challenge/tree/master/react-blog`

2. **Fix the Code and Implement Pagination:**
   - Address issues and add pagination feature to the blog.



## Tasks
#### 0. Server status
**#advanced**
- I just started a new Flask project and the first thing I’m putting in place is a route for the status of my API (super important for a load balancer implementation).
- But I don’t know why it’s not working…
- Could you look at it and fix it please?
- My code is here [here](https://github.com/alx-tools/0x01-Fix_My_Code_Challenge/tree/master/status_server/)
```
$ python -m api.v1.app 
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
....
$ curl -XGET http://0.0.0.0:5000/api/v1/status
{
  "error": "Not found"
}
$
```
**File: status_server/**
   
#### 1. My square
**#advanced**
- I love geometry!
- Look my square [here](https://github.com/alx-tools/0x01-Fix_My_Code_Challenge/blob/master/square.py), it’s perfect? No? Should I change something?


**File: square.py**
   
#### 2. Step 2: User model
**#advanced**

- I’m running into a serious problem!
- I just start my OOP project and nothing works…
- Could you help me please? My code is here [here](https://github.com/alx-tools/0x01-Fix_My_Code_Challenge/blob/master/user.py),
- Thank you!

**File: user.py**
   
#### 3. Blog access
**#advanced**
- I finished and deployed my Rails blog but people are contacting me because they can’t access any of my blog posts… Weird, it works for me…
- Could you take a look and fix it? My code base is here [here](https://github.com/alx-tools/0x01-Fix_My_Code_Challenge/tree/master/blog).
- Also, when you’re done, could you add a new feature please?
- I would like to add a boolean online for each Post object with a default value true. With this boolean, I will be able to hide/show some blog posts from the listing. I will also need a way to change this boolean in the Post#edit route. Could you do this for me?
- Thank you!

**File: blog**
 
#### 4. Never leave the office
**#advanced**

- I’m coming back from 2 weeks of holidays in France and when I arrived at the office, the first words from my marketing co-worker were: “Hi, how was your holiday? by the way, I think I broke the website…”
- WHAT???
- Ok, let’s jump on it and fix it [here](https://github.com/alx-tools/0x01-Fix_My_Code_Challenge/tree/master/react-blog)!
- Arf, I have also the pagination to fix… I didn’t have time before my break to look at it…

**File: react-blog**
