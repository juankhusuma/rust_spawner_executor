![Alt text](1st_experiment.png)
The new message  that is put under the spawner is printed first to the terminal before all of the print statement above it. This is due to the first two print statement is placed on an asynchronous function that is called by the spawner. The spawner is a process that is running in the background and does not halt the main process, so the main function just proceed to the next instruction given, which is printing the last message. That's why the last message is printed first before the first two messages.