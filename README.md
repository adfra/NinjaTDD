# NinjaTDD
A framework to enable Test-Driven Development (TDD) in NinjaTrader 8.

The approach promoted in this repository is focussed on enabling the use of true TDD techniques and tools (Testing Frameworks such as NUnit, Visual Studios Test Runner, MOQ libraries etc.) when developing NinjaTrader 8 components (Indicators, Strategies or AddOns). It does so by providing a layer of adapters which allow for mocking of NinjaTrader objects and hence provides a testable code-base which custom code can be developed against.

A few attempts at providing a test framework have been published on GitHub at the time of writing this (2024). They all have in common that they require NT to be running to provide the NT harness in order to operate the code. This approach is different as it should allow code to compile and be testable independent of NT running.

What this is not:
- a way to test any NT internal capabilities
- ...


