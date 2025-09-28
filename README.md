 ```cpp
#include <string>
#include <vector>
#include <stack>
using namespace std;
class AboutMe{
public:
  AboutMe(string Onur, string Calisir){
    name = Onur;
    auto preferred_name = "Honor";
    lastname = Calisir;
    skills();
    interested_in();
  }
  ~AboutMe(){}
  void skills(){
    programming_languages.at(0) = "C++";
    programming_languages.at(1) = "Python";
    // programming_languages.at(2) = "Go";
    programming_languages.at(3) = "Matlab";
    software.at(0) = "Linux/Ubuntu";
    software.at(1) = "ROS1/ROS2";
  }
  void interested_in(){
    interests.push("Robotics");
    interests.push("Nvim");
    interests.push("");
  }
private:
  string name, lastname, undergrad, masters;
  vector<string> programming_languages, software;
  stack<string> interests;
};
```
<!---
onurcalisir27/onurcalisir27 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
