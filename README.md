<div align="center"> <img src="https://media.tenor.com/3vcj3xtK1Z0AAAAi/totoro-anime.gif" width="500"/> </div>

# Hey, I'm Mobina 

```
   C++/Rust Developer • Systems Programmer • Educator • Cat
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=800&lines=C%2B%2B%2FRust+Developer;low-level+systems+programming;Building+high-performance+systems;CS+Student)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mobina_Gholamrezaei-8B5CF6?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mobina-gholamrezaei)
[![Email](https://img.shields.io/badge/Email-Mobina12412%40gmail.com-A78BFA?style=flat-square&logo=gmail&logoColor=white)](mailto:Mobina12412@gmail.com)
[![Twitter](https://img.shields.io/badge/Twitter-%40ACatinPurple-C084FC?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/ACatinPurple)
[![Location](https://img.shields.io/badge/📍-Toronto%2C_Canada-8B5CF6?style=flat-square)](https://www.google.com/maps/place/Toronto)

## Me

**Computer Science student at York University** and I code I guess? I'm a passionate developer who loves building cool projects and solving problems. (They say)

I'm passionate about **systems programming**, **high-performance computing**, and building elegant solutions to complex problems. I believe in continuous learning, teaching, and creating impactful software.

```cpp
namespace Mobina {
    struct Profile {
        std::string role = "C++/Rust Systems Developer";
        std::vector<std::string> passions = {
            "High-Performance Computing",
            "Distributed Systems & Microservices", 
            "Machine Learning Engineering",
            "Teaching & Mentoring"
        };
        int cpp_experience = 6;  // years
        int python_experience = 5;  // years
        bool loves_cats = true;  // always
    };
}
```

## 🛠️ Tech Stack

**Primary Languages**  
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Also Proficient In**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)

**Databases**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)

**Frameworks & Libraries**  
![Boost](https://img.shields.io/badge/Boost-F7901E?style=flat-square&logo=boost&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4285F4?style=flat-square&logo=google&logoColor=white)
![Protobuf](https://img.shields.io/badge/Protobuf-4285F4?style=flat-square&logo=google&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Development Tools**  
**Development Tools**  
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)

**Currently Learning**  
Abseil • Apache Thrift • Microservices Architecture • Advanced Rust

## 🚀 Featured Projects

### [Course Management System](https://github.com/mobinaghrz/Course-Management-System)
**Advanced University Platform with Multithreading** • `C++17`

Production-ready course management system handling students, courses, instructors, and enrollments with thread-safe operations and persistent storage. Demonstrates advanced OOP, STL mastery, and concurrent programming.

```cpp
class Database {  // Thread-safe Singleton
    std::unordered_map<int, std::shared_ptr<Student>> students;  // O(1) lookup
    std::unordered_map<int, std::unique_ptr<Course>> courses;
    std::mutex dbMutex;  // Concurrent access protection
    
    std::future<Student*> searchStudentAsync(const std::string& name);
};
```

**Technical Highlights:**
- **OOP Design:** Abstract base classes, polymorphism, inheritance hierarchy
- **Memory Safety:** Smart pointers (`shared_ptr`, `unique_ptr`), RAII principles, Rule of Five
- **Concurrency:** Thread-safe Singleton with `std::mutex`, `std::async` for async operations
- **STL Mastery:** `unordered_map` for O(1) lookups, `vector`, `set`, custom templates
- **Data Persistence:** Binary file I/O with object serialization
- **Exception Safety:** Custom exception classes, strong guarantee
- **Scalability:** Handles 10,000+ students, 50,000+ enrollments

---

### [Smart Route Optimization](https://github.com/mobinaghrz/Smart-Route-Optimization)
**Graph Algorithms + Machine Learning** • `C++` • `Python`

Intelligent route optimizer combining classical algorithms with ML for real-time traffic adaptation. Implements Dijkstra's, A*, and Q-Learning with historical traffic prediction using Decision Trees.

```cpp
class RouteOptimizer {
    Graph cityMap;  // Adjacency List/Matrix
    PriorityQueue<Path> paths;  // Min-Heap
    QLearningAgent trafficAgent;  // Dynamic weight adjustment
};
```

**Technical Highlights:**
- Dijkstra's Algorithm & A* for pathfinding
- Reinforcement Learning (Q-Learning) for traffic patterns
- Priority Queues (Heap) for efficient path selection

---

### [DataSculptor](https://github.com/mobinaghrz/DataSculptor)
**Intelligent Data Compression** • `C++` • `Machine Learning`

Adaptive compression tool that learns file patterns to achieve optimal compression ratios. Uses Huffman encoding enhanced with LSTM predictions for dynamic tree weight adjustment.

```cpp
struct HuffmanTree {
    TrieNode* compressionMap;
    PriorityQueue<Node> minHeap;
    LSTMModel patternPredictor;  // ML-driven optimization
};
```

**Technical Highlights:**
- Huffman Trees for optimal encoding
- Tries for efficient compression mappings
- LSTM model for pattern prediction

---

### [RecSys-Collab-Filtering](https://github.com/mobinaghrz/RecSys-Collab-Filtering)
**Recommendation System** • `C++`

High-performance recommendation engine using collaborative filtering and matrix factorization. Optimized for large-scale user-item interactions with SVD dimensionality reduction.

```cpp
class RecommendationSystem {
    Graph userItemGraph;  // User-item interactions
    Matrix svdFactors;  // Dimensionality reduction
    PriorityQueue<Item> topK;  // Fast top-k recommendations
    HashMap<int, User> userCache;  // O(1) lookups
};
```

**Technical Highlights:**
- Graph representation of user-item relationships
- Matrix Factorization (SVD) for scalability
- Hash Maps for O(1) lookups
- Built from scratch without external ML libraries

---

### [Image Classification with Custom Decision Tree](https://github.com/mobinaghrz/Image-Classification-Decision-Tree)
**Computer Vision** • `C++`

Image classifier using custom decision tree implementation with feature extraction (color histograms, edge detection). Includes pruning techniques to prevent overfitting.

```cpp
class DecisionTree {
    TreeNode* root;
    
    double calculateEntropy(const Dataset& data);
    TreeNode* buildTree(Dataset& data, int depth);
    void prune(TreeNode* node);  // Prevent overfitting
};
```

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats-eight-theta.vercel.app/api?username=mobinaghrz&theme=shades-of-purple&hide_border=false&include_all_commits=true&count_private=true)
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=mobinaghrz&theme=shades-of-purple&hide_border=true)
![Top Languages](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=mobinaghrz&theme=shades-of-purple&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

</div>

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=mobinaghrz&theme=react-dark&hide_border=true&area=true&color=A78BFA&point=8B5CF6&custom_title=Contribution%20Timeline)


## 🌱 Currently Learning

- **Machine Learning** - Stanford Certificate (Expected Dec 2025)
- **Distributed Systems** - gRPC, Protobuf, Microservices
- **Rust** - Systems programming with memory safety
- **Google's C++ Stack** - Abseil, High-Performance Computing

## 💡 What I'm Working On

```cpp
namespace CurrentProjects {
    struct Focus {
        // Building production-grade C++ systems
        Project courseManagementV2 = {
            .features = {"REST API", "Database Integration", "Web Interface"},
            .tech = {"C++20", "Boost.Beast", "PostgreSQL"}
        };
        
        Project distributedSystem = {
            .learning = {"gRPC", "Microservices", "High-Performance RPC"},
            .goal = "Google-scale system design"
        };
        
        // Deepening systems knowledge
        std::vector<std::string> exploring = {
            "Rust for systems programming",
            "Advanced concurrency patterns",
            "Lock-free data structures",
            "Memory optimization techniques"
        };
        
        // Career targets
        std::set<std::string> targeting = {"Google", "Pinterest", "Meta"};
    };
}



```

<div align="center">

```
  /\_/\  
 ( o.o ) 
  > ♡ <
"My code has better exception handling than I do."
```

[![Profile Views](https://komarev.com/ghpvc/?username=mobinaghrz&color=blueviolet&style=flat-square)](https://github.com/mobinaghrz)

</div>
