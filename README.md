<img src="https://github.com/AdamCassidy/GreenThumb/blob/master/resources/logo.png" alt="logo" width="300"/>  

## [Link to Documents](https://aarone314.github.io/CP317-Project-Green-Thumb/)

# Demo
## Running the API
To run the API:
1. Run api.js.
2. Open the command line.
3. Run ```ngrok http 2500``` in the command line.
4. Requests can now be sent to the URL displayed.

## Sending a Request to the API
To send a request to the API (for testing purposes):
1. Go to [apitester.com](apitester.com).
2. Switch from "GET" to "POST" request.
3. Add the following header: ```Content-Type```. It must have the following value: ```application/json```. This tells the API that there will be a request body ("Post Data") in JSON format.
4. Fill out the body in valid JSON format.
5. Make the request.
6. Check that the request returned the expected body.

</br>
</br>


## Branch Structure

The branches go as follows,

## Master Banches

* Master -> Docs
* Master-Android -> Main Frontend branch
* Master-Backend -> Main Backend Branch

## Feature Branches

When you are working on a feature (something you are adding to the code), create a feature branch with the following naming scheme

`feature-"Android/Backend"-"Name of feature"`

eg:
 * feature-Backend-MachineLearning
 * feature-Android-SettingScreen
   
## Testing Branches

branches to be used for testing

* backend-Testing
* Android-Testing

## Merging Branches

When your done a feature create a pull request on github to merge the branch into the appropreate testing branch.
