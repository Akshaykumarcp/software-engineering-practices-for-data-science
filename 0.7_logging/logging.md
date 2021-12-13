# Logging

- Logging is valuable for understanding the events that occur while running your program. 
- For example, if you run your model over night and see that it's producing ridiculous results the next day, log messages can really help you understand more about the context in which this occurred. Lets learn about the qualities that make a log message effective.

# Log Messages

- Logging is the process of recording messages to describe events that have occurred while running your software. Let's take a look at a few examples, and learn tips for writing good log messages.

    Tip: Be professional and clear
    ```
    Bad: Hmmm... this isn't working???
    Bad: idk.... :(
    Good: Couldn't parse file.
    ```
    Tip: Be concise and use normal capitalization
    ```
    Bad: Start Product Recommendation Process
    Bad: We have completed the steps necessary and will now proceed with the recommendation process for the records in our product database.
    Good: Generating product recommendations.
    ```
    Tip: Choose the appropriate level for logging

    <strong>DEBUG</strong> - level you would use for anything that happens in the program.

    <strong> ERROR </strong> - level to record any error that occurs

    <strong> INFO </strong> - level to record all actions that are user-driven or system specific, such as regularly scheduled operations

    Tip: Provide any useful information
    ```
    Bad: Failed to read location data
    Good: Failed to read location data: store_id 8324971
    ```