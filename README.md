# Tee_Time_Requests
Python Requests to Automate Tee Time Selection 


# Purpose 
In a previous project I completed Tee Time Automation using Python Requests library. The challenge with Selenium is it slower when running in a virtual environment and the button locations/names change based on the size of the browser window. This was another learning opportunity to work on a real world problem with "messy" inputs. 

# Method 
By using the inspect method on a web browser and looking at the GET and POST requests sent to the URL I was able to recreate the process of booking a tee time with Python Requests. 

# Learnings 
Working with JSON responses to understand the responses from the website and leveraging the response for future requests. Preventing hard coding these variables in allow the code to be more robust when player # or cost changes. There are many network signals that occur, parsing through the relevant GET and POST requests to execute the action was a good learning experience. 
