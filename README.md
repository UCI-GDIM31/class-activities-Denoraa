# in-class-activities
## Devlogs
### W1
Write your W1 activity Devlog here.
Hello World.
### W2
1.Because RGB colors can't goes more than 1, so we need decimals to represent the color
2.Becuase Bounces is the number of times that ball jumps, so 1,2,3,4,5,...
3.Missing ;
### W3
Table 4 rhythm game : 
public bool DidPlayerHitBeat(float playerHitTime, float noteTime){

	if(playerHitTime == noteTime){
		return true;
	}
	else{
		return false;
	})

}
### W4
Tables 11-19: lines 17, 28, and 32

	private bool _isGrounded = true; // line 17: initializes the _isGrounded  private variable to true, indicating that the player starts on the ground.
	if (Input.GetKeyDown(KeyCode.Space) && _isGrounded)// line 28: checks if the space key is pressed and if the player is grounded before allowing a jump.
	_isGrounded = false;// line 32: sets the _isGrounded variable to false when the player jumps, indicating that the player is no longer on the ground.

### W5
Question: why do we use vector instead of more integers?

Answer: vectors are used to structure multi-dimensional data (like position and direction) for simplified math operations and seamless engine interaction, gives more clarity over separate numbers.

DeerW5 Devlog:
	Goal: Get the deer to walk to a specific spot using the game's built-in navigation system (NavMesh).

	Plan:

	Stuff we need (Variables): We'll use a Transform called _target so we can pick the spot in the Unity editor. We also need a NavMeshAgent called _agent to actually move the deer.

	When to run (Method): We only need the Start() method because the deer just needs the destination set when the game begins.

	Action: In Start(), we grab the _agent component, and then tell it to go to _target.position.

	Result: The DeerW5 script works! The deer now heads straight for the object we choose in the Inspector when the game starts. Done GGs
## Open-Source Assets
### W1
- Animals: https://assetstore.unity.com/packages/3d/characters/animals/animals-free-animated-low-poly-3d-models-260727 
- Low-poly environment: https://assetstore.unity.com/packages/3d/environments/landscapes/low-poly-simple-nature-pack-162153 