# GSerializer
A light weight JSON serializer

# Usage

##### Create class
```c#
public class Person
{
  public string First_Name { get; set; }
  public string Last_Name { get; set; }
  public int Age { get; set; }
}
```

##### Create instance of class
```c#
Person person = new Person()
{
  First_Name = "Tom",
  Last_Name = "Cruise",
  Age = 58
};
```

##### Pass the instance to `Serialize` method of `GJsonConvert` class  
```c#
string json = GJsonConvert.Serialize(person);
```
