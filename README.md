# Ex04 Places Around Me
## Date:3.05.2026

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
 map.html

<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Banglore</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Franklin.F(212224240041)</b></font>
</h3>
<center>

<img src="map.jpg" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Shivaji Nagar" title="Shivaji Nagar" href="nagar.html" coords="846,328,47" shape="circle">
    <area target="" alt="Banglore Palace" title="Banglore Palace" href="palace.html" coords="651,111,42" shape="circle">
    <area target="" alt="Modern Art Gallery" title="Modern Art Gallery" href="gallery.html" coords="658,267,35" shape="circle">
    <area target="" alt="Planetarium" title="Planetarium" href="planet.html" coords="676,331,36" shape="circle">
    <area target="" alt="Park" title="Park" href="park.html" coords="571,392,69" shape="circle">
</map>
</center>
</body>
</html>


gallery.html


<!DOCTYPE html>
<html>
<head>
    <title>Modern Art Gallery</title>
    <style>
        body {
            background-color: green;
            color: white;
            text-align: center; /* Centers text and inline elements like <img> */
            font-family: Arial, sans-serif;
        }

        h1 {
            text-transform: lowercase;
            margin-top: 20px;
        }

        i {
            display: block;
            margin: 20px auto;
            font-style: italic;
            font-size: 18px;
        }

        img {
            display: block;
            margin: 20px auto; /* centers image */
            border-radius: 10px;
            width: 700px;
            height: 400px;
            object-fit: cover;
        }
    </style>
</head>
<body>
    <h1>information</h1>
    <i>It houses a major collection of modern and contemporary Indian art—paintings, sculptures, graphic prints, and photography—from the 18th century up to the present day.</i>
    <img src="gallery.jpg" alt="Modern Art Gallery">
</body>
</html>


nagar.html

<!DOCTYPE html>
<html>
<head>
    <title>Shivaji Nagar</title>
</head>
<body text="white" bgcolor="green">
    <h1>information</h1>
    <i>
        Gothic Revival, with majestic pointed arches, ornate stained-glass windows, and soaring spires. 
        It’s the oldest church in Bengaluru and the only Basilica in the Archdiocese of Bangalore. 
        A major commercial zone: lots of street-shops, markets, wholesale outlets (especially clothing, fabrics, home goods). 
        For example, the “Shivajinagar Shopping Complex” is a well-known shopping area.
    </i>

    <div style="text-align: center; margin-top: 20px;">
        <img src="nagar.jpg" height="400" width="700" alt="Shivaji Nagar">
    </div>
</body>
</html>


palace.html

<!DOCTYPE html>
<html>
<head>
    <title>Bengaluru Palace</title>
</head>
<body text="white" bgcolor="green">
    <h1>information</h1>
    <i>
        Built in 1878, Bengaluru Palace was inspired by England’s Windsor Castle. 
        It was constructed by Rev. Garrett, the first principal of the Central High School 
        (now Central College, Bengaluru). Later, it was purchased by the Maharaja of Mysore, 
        Chamaraja Wadiyar, who expanded and renovated it into a royal residence. 
        The palace still belongs to the Mysore royal family.
    </i>

    <div style="text-align: center; margin-top: 20px;">
        <img src="palace.avif" height="400" width="700" alt="Bengaluru Palace">
    </div>
</body>
</html>


park.html

<!DOCTYPE html>
<html>
<head>
    <title>Freedom Park</title>
</head>
<body text="white" bgcolor="green">
    <h1>information:</h1>
    <i>
        Freedom Park in Bengaluru is a public park on the site of the former Central Jail, which was built by the British in 1866 and served as a prison for freedom fighters and political leaders. 
        Inaugurated in 2008, it is now a 21-acre public space featuring historical prison elements like watchtowers and gallows alongside modern amenities such as gardens, a jogging track, and a children's play area. 
        The park is also a hub for public expression and cultural events.
    </i>

    <div style="text-align: center; margin-top: 20px;">
        <img src="park.png" height="400" width="700" alt="Freedom Park">
    </div>
</body>
</html>


planet.html

<!DOCTYPE html>
<html>
<head>
    <title>Bengaluru Planetarium</title>
</head>
<body text="white" bgcolor="green">
    <h1>information</h1>
    <i>
        The Jawaharlal Nehru Planetarium (JNP) in Bengaluru is a premier institution for science popularization and education, 
        featuring a 15m dome Sky Theatre, a Science Centre with interactive exhibits, and a Science Park with over 50 outdoor exhibits. 
        Administered by the Bangalore Association for Science Education (BASE), it offers shows in English and Kannada, workshops for children, 
        and a variety of other programs to educate the public about astronomy and space science.
    </i>

    <div style="text-align: center; margin-top: 20px;">
        <img src="planetarium.jpg" height="400" width="700" alt="Bengaluru Planetarium">
    </div>
</body>
</html>

```

## OUTPUT

<img width="1919" height="1196" alt="image" src="https://github.com/user-attachments/assets/7fe7cd43-a654-43fd-8a81-d5147b634382" />
<img width="1280" height="560" alt="image" src="https://github.com/user-attachments/assets/78694f57-b837-4779-90a9-427dd6e36553" />
<img width="1280" height="609" alt="image" src="https://github.com/user-attachments/assets/0753a880-65fb-424d-8479-a54dfd7df4d0" />
<img width="1280" height="609" alt="image" src="https://github.com/user-attachments/assets/3e781634-bea5-4553-84d5-db71387a3575" />
<img width="1280" height="536" alt="image" src="https://github.com/user-attachments/assets/66893b3e-2555-454c-9bfc-1aa827ab5f7e" />
<img width="1280" height="508" alt="image" src="https://github.com/user-attachments/assets/79e08169-aec3-4ede-b777-2320c827323d" />


## RESULT
The program for implementing image maps using HTML is executed successfully.
