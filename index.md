# 10 Days Internship for Govt Polytechnic, Kunnamkulam from 08-05-23 to 20-05-23

## DAY 1(8-05-2023)
1. Created a github account

2. Created a profile 

**3. Basic syntax of github:-**

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-11%2012-08-09.png)


## DAY 2(9-05-2023)

 **PROGRAM 1:-Tinkercad,blinking of led without switch**
 
![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-09%2013-03-54.png)

[Tinker this blinking of led](https://www.tinkercad.com/things/d68hBdWGSBX)

**PROGRAM2:- Tinkercad,blinking of led with switch**

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-09%2012-39-49.png)

[Tinker this blinking of led with switch](https://www.tinkercad.com/things/6wbSky5emDK)


## DAY 3(11-05-2023)

**PROGRAM 3:- Tinkercad,blinking of led with AND gate(IC 7408)**

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-11%2010-44-29.png)

[Tinker this blinking of led weith an AND gate(IC 7408)](https://www.tinkercad.com/things/36RnXE8gj9i)


**PROGRAM 4:- Tinkercad,blinking of led with an ARDUINO**

```

// C++ code
//
void setup()
{
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop()
{
  digitalWrite(LED_BUILTIN, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED_BUILTIN, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
}
```

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-11%2011-16-02.png)

[Tinker this blinking of led with an ARDUINO](https://www.tinkercad.com/things/fTEVD2KHXuQ)

**PROGRAM 5:- Tinkercad,blinking of 2 led's with delay using an ARDUINO**

```

// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(13,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(150); // Wait for 1000 millisecond(s)
  digitalWrite(12,LOW);
  delay(150); // Wait for 1000 millisecond(s)
}

```

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-11%2012-57-12.png)

[Tinker this blinking of 2 led's with delay using an ARDUINO](https://www.tinkercad.com/things/67GfHPwgGPM)



**PROGRAM 6:- Tinkercad,blinking of 4 led's with delay using an ARDUINO**

```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
  pinMode(12, OUTPUT);
  pinMode(8,OUTPUT);
  pinMode(7,OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(13,LOW);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(150); // Wait for 1000 millisecond(s)
  digitalWrite(12,LOW);
  delay(150); // Wait for 1000 millisecond(s)
  digitalWrite(8,HIGH);
  delay(150); // Wait for 1000 millisecond(s)
  digitalWrite(8,LOW);
  delay(150); // Wait for 1000 millisecond(s)
  digitalWrite(7,HIGH);
  delay(150); // Wait for 1000 millisecond(s)
  digitalWrite(7,LOW);
  delay(150); // Wait for 1000 millisecond(s)
}
```

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-11%2014-22-45.png)

[Tinker this blinking of 4 led's with delay using an ARDUINO](https://www.tinkercad.com/things/9fzQegn6L8l)

## DAY 4(12-05-2023)

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-15%2015-05-51.png)


## DAY 5(15-05-2023)

**PROGRAM 7:- Tinkercad, working of analog potentiometer using an ARDUINO**

```

const int potPin = A0;

void setup() {
  Serial.begin(9600);
}

void loop() {
  int potValue = analogRead(potPin);
  Serial.println(potValue);
  delay(100);
}
  
  
```

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-15%2014-14-35.png)

[Tinker this working of analog potentiometer using an ARDUINO](https://www.tinkercad.com/things/cWcHioKYK4y)

**PROGRAM 8:- Tinkercad, working of 7 segment using an ARDUINO**

```

// C++ code
//
void setup()
{
  pinMode(2, OUTPUT);
  pinMode(3,OUTPUT);
  pinMode(4,OUTPUT);
  pinMode(5,OUTPUT);
  pinMode(6,OUTPUT);
  pinMode(7,OUTPUT);
  pinMode(8,OUTPUT);
}

void loop()
{
  digitalWrite(2, LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(4,LOW);
  digitalWrite(3,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(2,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(1000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(8,LOW);
  digitalWrite(6,LOW);
  digitalWrite(5,LOW);
  digitalWrite(7,HIGH);
  digitalWrite(4,HIGH);
  delay(1000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(8,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  delay(1000);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(2,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(5,HIGH);
  delay(1000);
  digitalWrite(2,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,HIGH);
  digitalWrite(3,HIGH);
  delay(1000);
  digitalWrite(2,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(3,HIGH);
  delay(1000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  digitalWrite(7,HIGH);
  digitalWrite(8,HIGH);
  delay(1000);
  digitalWrite(2,LOW);
  digitalWrite(3,LOW);
  digitalWrite(4,LOW);
  digitalWrite(5,LOW);
  digitalWrite(6,LOW);
  digitalWrite(7,LOW);
  digitalWrite(8,LOW);
  delay(1000);
  digitalWrite(5,HIGH);
  digitalWrite(6,HIGH);
  delay(1000);
  
  delay(1000); // Wait for 1000 millisecond(s)
}

```

![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-15%2015-32-59.png)

[Tinker this working of 7 segment using an ARDUINO](https://www.tinkercad.com/things/eOdNtEzZ7Br)


## DAY 6(16-05-2023)

**PROGRAM 9:- Tinkercad, created a 3D car design using basic shapes**


![no image](https://github.com/Nikhilskumar03/kunnamkulampolyintern/blob/main/image/Screenshot%20from%202023-05-18%2010-56-56.png)


[Tinker this 3D car design using basic shapes](https://www.tinkercad.com/things/g3jHmGlRQkh)


## DAY 8(18-05-2023)

**PROGRAM 10:- Tinkercad, working of 7 segment with a delay of the value of potentiometre using an ARDUINO**

![no image]()











