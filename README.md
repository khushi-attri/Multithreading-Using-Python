Threading allows the code to split the matrix multiplication task into smaller parts that can run concurrently. Each thread handles a portion of the matrix computation, sharing memory space and potentially improving performance by utilizing multiple CPU cores. The main function orchestrates the creation and execution of threads, measures their performance, and plots the results.

| No of Cores | Time Taken (sec) |
|-------------|-------------------|
| 1           | 2.631037950515747 |
| 2           | 1.5991008281707764 |
| 3           | 1.6040267944335938 |
| 4           | 1.462932825088501 |
| 5           | 1.456266164779663 |
| 6           | 1.4754681587219238 |
| 7           | 1.6305480003356934 |
| 8           | 1.6103200912475586 |
| 9           | 1.492563009262085 |
| 10          | 1.4714305400848389 |
| 11          | 1.5179014205932617 |
| 12          | 2.120454788208008 |
| 13          | 2.0628740787506104 |
| 14          | 2.0364909172058105 |
| 15          | 2.1577653884887695 |
| 16          | 2.2594406604766846 |
| 17          | 2.262118339538574 |
| 18          | 2.5261828899383545 |
| 19          | 2.189465284347534 |
| 20          | 1.9992599487304688 |


![download](https://github.com/khushi-attri/Multithreading-Using-Python/assets/97894347/431cd258-07d6-400b-a5c6-5dd9e86a4528)

![download](https://github.com/khushi-attri/Multithreading-Using-Python/assets/97894347/9d0deafd-6568-4a1f-acd5-bf79e2c7472e)
