# PC16 – Week 11: Asynchronous Programming in Dart

- **Student Name:** Caday, Ismael Haven R.
- **Year & Section:** 3.3-BSIT
- **Course:** NTC_PC16 – Mobile Development w/ Lab

---

## Description
This application extends our OOP vehicle application hierarchy from Week 10 by integrating Dart's asynchronous programming features (`Future`, `async`, and `await`)[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span). It demonstrates how to perform simulated time-consuming operations—such as running a system diagnostic scan—without blocking execution flow or freezing application logic[span_2](start_span)[span_2](end_span).

---

## Features & Rubric Alignment

- **Base Class & Inheritance (`Vehicle`, `ElectricCar`, `Motorcycle`):** Maintained the vehicle hierarchy featuring abstract contracts (`Startable`), encapsulation, method overriding, and mixins (`DiagnosticLogger`)[span_3](start_span)[span_3](end_span)[span_4](start_span)[span_4](end_span).
- **Async Method (`runFullSystemDiagnostic`):** Added an asynchronous method returning a `Future<String>` to simulate data processing or diagnostic checks[span_5](start_span)[span_5](end_span).
- **Simulated Delay (`Future.delayed`):** Incorporated a 2-second delay using `Future.delayed` inside the async method to simulate background work[span_6](start_span)[span_6](end_span).
- **Async/Await Integration (`main()`):** Updated `main()` to be marked `async` and awaited the diagnostic method call[span_7](start_span)[span_7](end_span).
- **Non-blocking Execution Proof:** Printed console output immediately before calling `await` to demonstrate that non-blocking tasks execute in order before the asynchronous operation resolves[span_8](start_span)[span_8](end_span).

---

## How to Run

### Run in Dartpad
- open dartpad.dev
- Copy & Paste the code from Week11_Add-Async-Behavior-to-Your-OOP-App_Code
- run

