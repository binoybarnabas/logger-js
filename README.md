# devlogging

## About the Package

**devlogging** is a lightweight logging utility designed for react developers to easily debug errors and important events during software development in the development environment. Say goodbye to cluttered `console.log()` statements – with devlogging, you can streamline your debugging process effortlessly in development mode and don't need to worry about deleting all those `console.log()` that you have used to debug; .

## How to Use

Using devlogging is simple:

1. **Install** the package using npm or yarn:
    ```bash
    npm install devlogging
    ```

2. **Import** devlogging in your project:
    ```javascript
    import { logger } from 'devlogging';
    ```

3. **Start logging/debugging** in the development environment:
    ```javascript
    logger.log('This is a log message.');
    logger.error('This is an error message.');
    logger.info('This is an info message.');
    logger.warn('This is a warning message.');
    ```



## Contributing

Contributions are welcome! Please feel free to submit bug reports, feature requests, or pull requests via the [GitHub repository](https://github.com/binoybarnabas/logger-js.git).


