# Runtime Objects

Runtime Objects are at the core of the entire Scriptable Framework's easy drag and drop workflow. They **inherit** from the `ScriptableObject` class defined by Unity which you can learn more about [here](https://learn.unity.com/tutorial/introduction-to-scriptable-objects).

You can think of Runtime Objects like prefabs of data. They exist in your assets folder and can be referenced by any MonoBehaviour script in any one of your scenes. This allows you as a developer to take advantage of them in a lot of unique ways that are simply not possible with the conventional style of scripting in Unity. So much so that an entire framework can be developed using Scriptable Objects!

They are called "runtime" objects because of how data stored within them is automatically cleared at the start and end of runtime (when your application is running). They are intended to act as containers of data that you can "inject" into the scripts in your scene that "depend" on them (dependancy injection). This flexibility lets you swap around references with dummy data or real data to more easily test your code as well as other things you can read more about in this manual. 