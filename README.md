# GSerializer
A light weight JSON and XML serializer

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
  First_Name = "Gaurav",
  Last_Name = "Babbar",
  Age = 27
};
```

##### Pass the instance to `Serialize` method of `GJsonConvert` class  
```c#
string json = GJsonConvert.Serialize(person);
```
