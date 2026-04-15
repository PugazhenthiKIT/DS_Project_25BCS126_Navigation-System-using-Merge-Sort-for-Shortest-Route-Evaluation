Problem Statement

In real-world navigation systems, multiple routes are available between a source and destination. Each route may have different distances and traffic conditions, which affect travel time.

Manually selecting the best route is difficult and inefficient when many options exist. Hence, a system is needed to automatically evaluate and sort routes based on travel time.

This project solves the problem by using the Merge Sort algorithm to efficiently determine the shortest and fastest route.

🧠 Data Structures & Algorithms Used
Data Structures
Array / List
Used to store route details such as:
Route name
Distance
Traffic level
Travel time
Algorithms
Merge Sort Algorithm
Used to sort routes based on travel time efficiently (Divide and Conquer method)
Linear Search Algorithm
Used to search for a specific route by name
⚙️ How to Compile and Run
Requirements
Python 3.x installed
Steps to Run
Open terminal or command prompt
Navigate to project folder
Run the program using:
python navigation_system.py
Enter route details when prompted
View sorted routes and search results
🧪 Sample Input / Output
Sample Input
Enter number of routes: 3

Route 1:
Name: RouteA
Distance: 10
Traffic Level: 2

Route 2:
Name: RouteB
Distance: 5
Traffic Level: 3

Route 3:
Name: RouteC
Distance: 8
Traffic Level: 1
Sample Output
Sorted Routes (by Travel Time):
RouteC → Time: 8
RouteA → Time: 20
RouteB → Time: 15

Search Route:
Enter route name: RouteA

Route Found!
Name: RouteA
Distance: 10
Traffic: 2
Time: 20
⏱️ Time and Space Complexity
Merge Sort
Time Complexity:
Best Case: O(n log n)
Average Case: O(n log n)
Worst Case: O(n log n)
Space Complexity:
O(n) (extra memory required for merging)
Search Algorithm
Time Complexity: O(n)
Space Complexity: O(1)
✅ Conclusion

This project demonstrates how the Merge Sort algorithm can be applied in real-world navigation systems to efficiently find the shortest route. It improves decision-making and reduces travel time.
