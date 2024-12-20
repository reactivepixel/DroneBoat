```
Class Boat {
    float speed;
    float heading;
    boolean isRunning

    Engine leftEngine;
    Engine rightEngine;


    void startEngines() {
        leftEngine.start();
        rightEngine.start();
        isRunning = true;
    }
}


```