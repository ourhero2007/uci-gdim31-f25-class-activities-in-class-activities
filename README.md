# GDIM 31 In-Class Activities
## W1
### Activity 1 
One thing my table group had in common was that we were all children of immigrant parents. 

### Activity 2
1. Unlike when the camera was the child of the Cat, the camera no longer follows the cat wherever it moves. It stays in the same position because it's not connected to the Cat GameObject.

2. https://ourhero2007.itch.io/i-am-a-cat

## W2
Floats are the variable category for variables that are set to decimal numbers. Since int is only for integers, bools are for true and false statements, and strings are for displayed text, we wouldn't use those because it's categorizing the variable wrong. If you do that you'll get an error.
The _bounce variable is an int because the bounces are counted as integers (whole numbers), they wouldn't be float because that variable is for decimal numbers. It wouldn't be bool because that's for true/false statements and it wouldn't be string because that's for displayed text.
The error for Step 4 was that there was no semicolon at the end of the line. 

## W3 
### Activity 1 - Table 6 
Imagine we need to design a method to perform the following function. What would you make the parameters (input) and return type (output) of this method?
1. My answer: Parameters would be float for friendship level and boolean for whether the player knows the character's secret. Friendship level would most likely be measured by a certain number, and the question of knowing the character's secret is a yes/no (AKA true/false) question. Return type would be string for the dialog.

	Class answer: public string GetResponse(int/float friendshipLevel, bool knowsSecret)

2. My answer: Parameters would be float for the percentage numbers, and the return type would be void. 

	Class answer: void SetLightDimness(float sanityLevel) 

3. My answer: Parameters would be float for time, and the return type would be boolean. 

	Class answer: public bool DidHitBeat(float timeHit)

### Activity 2 - Table 6 
Classes are like the blueprints for an architectural project, while the Components are the physical building materials we are putting together to make the building, member variables are the certain traits or style of the building, and methods are the tools we use to build.

### Activity 3 
The balls get extremely bright the more they bounce because the GetColorMultiplier method multiplies how much the color increases intensity which means it increases exponentially. 

## W4 - Table 6 
1. We added the Rigidbody component to the Cat and SoccerBall gameobjects, and checked Is Trigger for the Collider component on the Goal gameobject. This is because we want the game to know when the ball has gone through the goal, but we don't want there to be a physical block that stops the ball from entering. So instead of just a Collider, the Goal is also marked as a Trigger. We use Rigidbody on the Cat and SoccerBall because when they interact we want them to follow game physics.  
2. Despite writing the code for updating points and the point text, when testing it did not update. This was because I did not properly write the code for updating the points text, which I figured out and fixed. 

## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 
