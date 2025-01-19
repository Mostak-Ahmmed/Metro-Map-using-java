# Dhaka Metro Map Project  

This project is a Java-based application that simulates a representation of the Dhaka Metro Map using graph data structures. It provides functionalities to display the metro map, list all available stations, and determine paths between stations. Additionally, it implements Dijkstra's Algorithm for finding the shortest path.  

## Features  

### 1. Display Metro Map  
- The `display_Map` method prints the entire metro map, showing each station and its connected neighbors with their respective distances.  

### 2. Display Available Stations  
- The `display_Stations` method lists all available metro stations in a numbered format for easy reference.  

### 3. Check Path Existence  
- The `hasPath` method determines whether a path exists between two given stations.  

### 4. Dijkstra's Algorithm  
- A private inner class `DijkstraPair` is implemented to facilitate finding the shortest path between two stations. The method uses a priority queue to compute the least-cost path efficiently.  

## Key Components  

### Methods  
- **`display_Map()`**: Prints the Dhaka Metro map with connections and distances.  
- **`display_Stations()`**: Lists all stations in the metro network.  
- **`hasPath(String vname1, String vname2, HashMap<String, Boolean> processed)`**: Recursively checks if a path exists between two stations.  
- **DijkstraPair**: Implements `Comparable` for comparing the cost of paths to determine the shortest route.  
