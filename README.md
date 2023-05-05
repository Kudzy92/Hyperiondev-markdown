# Hyperiondev-markdown

### Section A

```python
class Solution:
       def groupAnagrams(self, strs):
      result = {}
      for i in strs:
         x = "".join(sorted())
         if x in result:
            result[x].append(i)
         else:
            result[x] = [i]
      return list(result.values())
ob1 = Solution()
print(ob1.groupAnagrams(["eat", "tea", "tan", "ate", "nat", "bat"]))
```

#### NOTES

1.  Classname should be informative  `class AnagramSolution:`
2.  Your should indent your code to avoid IndentationError. Just like

```python
class Solution:
    def groupAnagrams(self, strs):
         result = {}
         for i in strs:
             x = "".join(sorted(i))
         if x in result:
             result[x].append(i)
         else:
             result[x] = [i]
         return list(result.values())
ob1 = Solution()
print(ob1.groupAnagrams(["eat", "tea", "tan", "ate", "nat", "bat"]))
```

### Section B: Projects

Annies' Design is an ecommerce website for a furniture shop.The website was developed using ReactJs, CSS, JavaScript as the frond end technologies and also Express, MongoDB was used as the backend technologies

Github repository link for frontend.  
Open [https://github.com/Kudzy92/anniesdesign-front](https://github.com/Kudzy92/anniesdesign-front) to see the source code.

Github repository link for backend.  
Open [https://github.com/Kudzy92/anniesdesign-backend](https://github.com/Kudzy92/anniesdesign-backend) to see the source code.

Preview Link.  
Open [https://anniesdesign-front.vercel.app](hhttps://anniesdesign-front.vercel.app) to preview.
