# Adder example
The verification environment is setup using Vyoma's UpTickPro provided for the hackathon.

Make sure to include the Gitpod id in the screenshot


## Screenshots
![App Screenshot](Screenshot%20(1159).png)


## Verification Environment

The CoCoTb based Python test is developed as explained. The test drives inputs to the Design Under Test (adder module here) which takes in 4-bit inputs a and b and gives 5-bit output sum

The values are assigned to the input port using

```bash
  dut.a.value = 7
  dut.b.value = 5
```


