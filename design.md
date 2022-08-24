# {{PROBLEM}} Multi-Class Planned Design Recipe

## 1. Describe the Problem

As a user
So that I can record my experiences
I want to keep a regular diary

As a user
So that I can reflect on my experiences
I want to read my past diary entries

As a user
So that I can reflect on my experiences in my busy day
I want to select diary entries to read based on how much time I have and my reading speed

As a user
So that I can keep track of my tasks
I want to keep a todo list along with my diary

As a user
So that I can keep track of my contacts
I want to see a list of all of the mobile phone numbers in all my diary entries

----
NOUNS
diary
entry
todo list
task
phone number

VERBS
list entries
find optimal entries
list todos
list phone numbers
----



## 2. Design the Class System

_Consider diagramming out the classes and their relationships. Take care to
focus on the details you see as important, not everything. The diagram below
uses asciiflow.com but you could also use excalidraw.com, draw.io, or miro.com_

```ruby

class Diary
  def initialize
    # list of entries
  end

  def add(entry) # entry is a string    
    # add entry to list of entries
    # returns nothing
  end

  def find_optimal_entry
    # methods TBC
  end

  def scan_for_numbers
    # scans for numbers 
  end
end

class TodoList
  def initialize
    # list of tasks
  end

  def add(task)
    # adds task
    # returns nothing
  end

  def list
    # returns all tasks
  end 
end

class Task
  def initialize
    # task as string
  end
  
  def task
    # returns task as string
  end  
end

class PhoneBook
  def initialize
    # list of numbers
  end

  def add(number)
    # adds number
    # returns nothing
  end

  def list
    # returns all numbers
  end 
end

class PhoneNumber
  def initialize
    # number as string
  end
  
  def task
    # returns number as string
  end  
end

```

## 3. Create Examples as Integration Tests

_Create examples of the classes being used together in different situations and
combinations that reflect the ways in which the system will be used._

```ruby
# diary = Diary.new
# entry = diary.add
# switching over to Jovi's project for phase2 bite9 exercise1 (15:22 24-Aug-2022)
```

## 4. Create Examples as Unit Tests

_Create examples, where appropriate, of the behaviour of each relevant class at
a more granular level of detail._

```ruby

```

_Encode each example as a test. You can add to the above list as you go._

## 5. Implement the Behaviour

_After each test you write, follow the test-driving process of red, green,
refactor to implement the behaviour._