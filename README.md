### Getting Started
* Download & install [open frameworks](https://openframeworks.cc/download/) for your system

* go to apps/

* Open a git bash here and run:
 `git clone https://github.com/oorahmi/WhackAMan`

# Important Concepts to Learn in Writing Software
* git / simple source control
* Common programming concepts (looping, conditionals, operators,)
* Data Structures When, Why, and How they work(Array, Linked List, Queue, Trees, Heaps, HashMaps)
* polymorphism vs component-based design
* simple algorithms (sorting, recursion)
* File I/O
* Debugging/Patience
* Threading
* How Computers run programs (function stack)
* Cache and Memory behaviour
* Dynamic Programming
* Testing effectively no TDD
* Functional programming
* Vim or Emacs / Which editor to use



# Requirements
 Implement a whack-a-mole style game where a man pops up and you have to click on him to whack him

### Game Management
- spacebar to start the game/ gui button to start game
  - bonus points - gui elements to exit game or options?
- Game lasts 1 minute. Display this using bitmap text
- Display points earned for whacking moles using bitmap text

- Record points where player clicked, store them in a data structure

### Game Elements
- Implement a mole/man spawner.
  * Can spawn multiple types of moles
    * One Mole has more health and time spent above ground(need to click multiple times)
      * bonus points if you can think of more interesting mole types, (ie mole that moves, mole that shields)
  * Spawns in random locations.
  bonus points - use data analysis to pick harder spots to place moles for the player to reach
  * Can only have a maximum of 5 moles spawned at any time

- Implement Moles
  * take damage on mouse click
  * have hp
  * alive/dead?


- Implement a binary search tree

### File Input/Output (I/O)
* Record Persistent statistics to a file and load them when the game starts
  * Highest score
  * Total mouse clicks
  * Total hits
  * Moles Killed

# Good Resources to keep in mind
These may be hard to grasp, but it should be a goal to understand where these ideas are coming from.
Basically all of these come from the video games field. IMO if you can program games, you can program anything. Games are very very difficult.
Games seem to be the most public field of programming that is looking to push the limits of what a computer can do.

* [Should I be making another method, why?](http://number-none.com/blow/blog/programming/2014/09/26/carmack-on-inlined-code.html)

* [Is software getting better?](https://www.youtube.com/watch?v=k56wra39lwA)

* [Be sure to Test effectively](https://www.youtube.com/watch?v=21JlBOxgGwY)

* [Game Programming Patterns](http://gameprogrammingpatterns.com/contents.html)

* [Data oriented design](https://www.youtube.com/watch?v=rX0ItVEVjHc)

* [Life optimization when programming is important](https://www.youtube.com/watch?time_continue=5&v=JjDsP5n2kSM)

As you can see I'm a big fan of Johnathan Blow's thoughts on programming.
Another good source for low-level stuff and thoughts on software in general is Casey Muratori, .