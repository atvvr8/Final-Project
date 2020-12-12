# Final-Project
<!DOCTYPE html>

<html>

<head>
	<title>Anna van Glabbeek</title>
</head>

<body>
	  <h2>About Myself</h2>
	  <p>I attend the University of Missouri, also known as <em>Mizzou</em>, which is located in central Missouri</p>
	  <a href="https://missouri.edu/" target="_blank">Mizzou's Website</a>

    <br> <img src="https://bloximages.newyork1.vip.townnews.com/stltoday.com/content/tncms/assets/v3/editorial/6/e9/6e9eae87-35d9-5219-b089-699de69e2d07/5a75172c61d42.image.jpg?crop=523%2C392%2C38%2C0&resize=1200%2C900&order=crop%2Cresize" height="240" width="320" /> 

    <p>The University has many majors to choose from including: <ul>
      <li>Information Technology</li>
      <li>Biology</li>
      <li>Business</li>
      <li>And many more</li>
      </ul>
      
      <p>Here is some code I made for a project for one of my IT classes made to find the position of an object: <br> <br>
        def get_initial_value(prompt): 
    value = float(input(prompt))
    return value

def calculate_final_position():
    initial_x = get_initial_value("Enter the initial position: ")
    initial_v = get_initial_value("Enter the initial velocity: ")
    acceleration = get_initial_value("Enter the acceleration: ")
    time = get_initial_value("Enter the time: ")

    final_position = initial_x + initial_v * time + .5 * acceleration * (time * time)
    return final_position
    
def main():
    final_position = calculate_final_position()
    print("The final position is:", final_position)

main()
</p>
      

</body>
