# Random Dog Viewer Challenge

## Goals

Create a simple JavaScript application that:
* Takes a number from the user
* Gets this number of random dog pictures from the Dog.CEO API.
* Displays these pictures, along with the breed of the dog.

## Background

https://dog.ceo/ hosts Dogs-as-a-Service, "the internet's biggest colleciton of open source dog pictures". Their publicly-available REST API has an endpoint that will return a random number of dog pictures. The URL for this endpoint is:

[https://dog.ceo/api/breeds/image/random/3](https://dog.ceo/api/breeds/image/random/3)

A call to this URL will return a JSON document similar to:

    {
        "message": [
            "https://images.dog.ceo/breeds/otterhound/n02091635_2766.jpg",
            "https://images.dog.ceo/breeds/spaniel-blenheim/n02086646_2366.jpg",
            "https://images.dog.ceo/breeds/waterdog-spanish/20180723_185559.jpg"
        ],
        "status": "success"
    }

You can also specify a specific breed:

[https://dog.ceo/api/breed/beagle/images/random](https://dog.ceo/api/breed/beagle/images/random)

## Requirements

1. Let the user enter a number of dogs to display.
2. Let the user optionally enter an arbitrary dog breed name.
3. Use these values to query the Dog.CEO Random Dog Image API. If the user has not specified a breed, query all breds.
4. Display the images and breed names of all dogs returned by this query.
5. Display the dog breed names in a user-friendly format.
    1. Replace all hyphens with spaces.
    2. Capitalize the first letter of each word.
6. Ensure that the code operates correctly in at least one modern browser. (ex: Chrome, Firefox.)
7. Add styling to make the UI look presentable.
8. Include unit tests to verify the functionality of your code.
9. Include a rough summary of how much time you spent on these tasks:
    * Setup & configuration
    * Coding
    * Testing
    * UI Design

Included in this challenge is an HTML file (dog-viewer.html) that you can use to start your user interface. You can modify this file as much as you like.
