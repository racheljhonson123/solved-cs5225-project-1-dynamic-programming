Download Link: https://assignmentchef.com/product/solved-cs5225-project-1-dynamic-programming
<br>
In this assignment, you will be asked to implement policy iteration and value iteration for the Frozen Lake environment from <a href="https://gym.openai.com/envs/#toy_text" rel="nofollow">OpenAI Gym</a> and play the game with the algorithms you implemented. This project will be completed in Python 3.

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project1/img/hw1.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project1/img/hw1.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project1/img/hw1.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>




<h2><a id="user-content-hints" class="anchor" href="https://github.com/bucky1995/CS_525_RL/tree/master/Project-1#hints" aria-hidden="true"></a>Hints</h2>

<ul>

 <li>Policy Evaluation<strong>Please note that reward can be defined on (state), (state, action), (state, action, next_state). In this assignment, we define the reward on (state,action,next_state).</strong> The following pseudocode is the general method.</li>

</ul>

<a href="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/blob/master/project1/img/pe.png?ssl=1" target="_blank" rel="noopener noreferrer"><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project1/img/pe.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" src="https://i0.wp.com/github.com/huiminren/DS595CS525-RL-HW/raw/master/project1/img/pe.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript></a>