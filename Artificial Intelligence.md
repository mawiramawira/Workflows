For each possible percept sequence, a rational agent should select an action that 
is expected to maximize its performance measure, given the evidence provided by
the percept sequence and whatever built-in knowledge the agent has
[]PART I: Frame the problem
    []Define the business objective
    []Define the task environment
        []Creating the external environment 
            []This will get information to our agent 
            []Perfomance measure
                []What would be the desirable properties for our agent to achieve
                    []Any intermediate and final goals?
            []Environment
                []What makes up this space
            []Actuators
                []How do we act upon the environment
            []Sensors
                []How do we receive feedback from the environment
        []Defining the internal environment
            []This is the information we need to define the agent function 
            []Does the agent have all the information it needs to come 
                to a certain action? Complete state of the environment?
                []Yes - Fully observable
                []To some extent - Partially observable
                []No - unobservable i.e. no sensors
            []How many agents interact in this environment
                []Yes - single agent
                []No - multiagent
                []Are they collaborating or competing?
            []If I choose action x with the intention to get to state y, is state y guaranteed?
                []Yes - deterministic
                []No - stochastic
            []Do previous actions affect the next state
                []Yes - sequential
                []No - episodic e.g. drunk man
            []Does the environment change as the agent makes their decision
                []Yes - dynamic
                []No - static
                []The perfomance can increase but the environment does not change - semi-dynamic
            []Is the state-space discrete? In steps?
            []Is the action-space discrete?
            []Is the percept-space discrete?
            []Does the agent know anything about how the environemnt acts. I might know the rules
                but do I know how to operate on them
                []Yes - known
                []No - unknown
    []Define the relationship between the agent and environment/nature of task
        []Initial state
        []Possible Actions
        []States
        []Transition state
            []Actions and expected consequences
        []Goal state
        []Any costs associated e.g. path cost
    []CODE the environment
        []Pseudocode first
        []Test
[]PART II: Defining the solution
    []Define the agent
        []Reflex based - fully observable environment
            []No need to store internal state
            []Just need to act according to the rules I been programmed with
            []An state will always have a predetermined action
        []Model based
            []Has to mantain internal state
            []Needs to know how the world evolves independently
            []Needs to know how its actions change the state of the world
        []Goal based agent
            []Has some set goals to pace its performance
        []Utility based
            []Every state has a happiness score
            []Moves to the state with the highest expected hapiness score
        []Hybrid 
            []A mixture of the above
    []Defining a learning algorithm
        []Try out different algorithms and agents
    []CODE the solution algorithm
        []Pseudocode first
        []Test
