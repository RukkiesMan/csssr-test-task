# csssr-test-task

The project is a test task by CSSSR company

## Condition

Slomux is a simple, broken Flux version.
You have a simple app written in React + Slomux.
That doesn't work with interval update settings.

Fix bugs and potentially problematic code, fix the application and comment on your decision.

When you click on "start", the stopwatch should start and after a specified time interval increase its value by the interval value.
When you click on "stop", the stopwatch must stop and reset its value.

## Fixed bugs

- [Subscribe after the component is created in connect function](https://github.com/rukkiesman/csssr-test-task/commit/6c8ab20c898517b9335ef10268cd6d23dfa8f651)
- [Correctly update currentInterval in reducer](https://github.com/rukkiesman/csssr-test-task/commit/52398849e4a43dafec083d1f6f5c57b49fbdc5a7)
- [Return state upon default in reducer](https://github.com/rukkiesman/csssr-test-task/commit/eaa7c5f0653b6f064fc031fc4e5b7c1ba3841299)
- [Correctly pass Slomux data to Interval](https://github.com/rukkiesman/csssr-test-task/commit/61d2eed192735368bbe9a4c90282acbb94790649)
- [Bind this to TimerComponent methods](https://github.com/rukkiesman/csssr-test-task/commit/cf7c6c87c79b6315090e988fe922c193578e6dc4)
- [Correctly pass currentInterval to Timer](https://github.com/rukkiesman/csssr-test-task/commit/8f7952733264a998f325c9a0df1d27858be5d280)
- [Correctly pass currentInterval to Interval](https://github.com/rukkiesman/csssr-test-task/commit/67d81c639a937ac8b55f905e4bd7b73c157fe62b)
- [Use setInterval for continuous timer operation in TimerComponent](https://github.com/rukkiesman/csssr-test-task/commit/0ee999f62b1da85c1cc43b779cd5348777ca4659)
- [Interval time update in seconds](https://github.com/rukkiesman/csssr-test-task/commit/c60a0c0e8ed313e4e4cbd844c85a0c677438a8a9)

## Improvements

- [Disable decreasing interval button when interval is equal 1](https://github.com/rukkiesman/csssr-test-task/commit/2823b698565865df885fa9fae0d22cdc012d8efa)
- [Disable start button when timer is started](https://github.com/rukkiesman/csssr-test-task/commit/b51efef85407b65dcddd9d521d8425ce26d4ae2e)
- [Disable stop button when timer isn't started](https://github.com/rukkiesman/csssr-test-task/commit/73446feb2f10f67e5fb8e8e10394ed28abd9d5ea)
- [Disable interval buttons when timer is started](https://github.com/rukkiesman/csssr-test-task/commit/a8f66ec4749d01b3ca87283f6dee43c676852df0)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
