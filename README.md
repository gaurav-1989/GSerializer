# GSerializer
A light weight JSON and XML serializer

# Usage

```
public class Person
{
  public string First_Name { get; set; }
  public string Last_Name { get; set; }
  public int Age { get; set; }
}

Person person = new Person()
{
  First_Name = "Gaurav",
  Last_Name = "Babbar",
  Age = 27
};

string json = GJsonConvert.Serialize(person);

{
  "First_Name": "Gaurav",
  "Last_Name": "Babbar",
  "Age": 27
}
```
