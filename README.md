# DwarfGameEngine
A simple renderer for making games and/or visualisations.

![image](https://user-images.githubusercontent.com/67780454/177040835-6a406302-bebf-4768-9dac-17dd326e47f7.png)

Yes it's got 3D rendering too, although it is very bad.


### Usage

__Cloning this repo__:
```
git clone --recursive https://github.com/Hyrdaboo/DwarfGameEngine.git
```

You will have to use eclipse because I haven't tested it elsewhere and I am not sure if it works

### Setting up
Here is a basic setup that you will need to get this engine up and running:

```Java
import DwarfEngine.Engine;

class Demo extends Engine {

	// Start is called at the beginning of the game
	public void OnStart() {
		
	}

	// update is called every frame
	public void OnUpdate() {
		
	}
}


public class Main {

	public static void main(String[] args) {
		Demo demo = new Demo();
		// Construct will create a window with defined width, height, pixel size(optional) parameters
		demo.Construct(200, 200, 2);
	}

}
```

The above code produces this result:

![image](https://user-images.githubusercontent.com/67780454/177041324-8cda50ac-dce0-489c-be63-2b3af402cce1.png)
