# ChessQy

Where is the best place to insert the queen figure?

1) Find the cell where the queen affects to minimum number of cells.
2) Insert a queen in that cell.
3) Remove all cells that are under the influence of the queen.
Repeat this algorithm until there aren't free cells

It's obvious that for n=1, there is a unique solution, and for n=2 and n=3, there is no solution.
Let's see what happens for n>3.

For n = 4, here is the solution:
![found_n=4](https://github.com/haykagha/ChessQy/assets/50166655/f5bb8bee-e8d1-4d29-9faf-031b0aeb794b)

And the illustration:
![illustration_n=4](https://github.com/haykagha/ChessQy/assets/50166655/5bbf3163-472d-4f15-ac01-0d082d1309f5)

For n = 5, here is the solution:
![found_n=5](https://github.com/haykagha/ChessQy/assets/50166655/451ebb69-c915-4200-adeb-b545c3920b83)

For n = 6, here is the solution:
![found_n=6](https://github.com/haykagha/ChessQy/assets/50166655/65d824f1-c200-4ec8-8215-421608da19d2)

For n = 7, here is the solution:
![found_n=7](https://github.com/haykagha/ChessQy/assets/50166655/c9007f11-44cc-470c-a073-298ba3d8f2c7)

For n = 8, here is the solution:
![found_n=8](https://github.com/haykagha/ChessQy/assets/50166655/f0fc9dee-a88b-4cbf-8ec7-a5a007896b7b)

And the illustration:
![illustration_n=8](https://github.com/haykagha/ChessQy/assets/50166655/149eee75-74c2-4075-bd36-3d305d8acb9b)

For n = 9, here is the solution:
![found_n=9](https://github.com/haykagha/ChessQy/assets/50166655/86deafc1-4875-4550-9b5c-68b957d1b039)


For n = 13, here is the solution:

![found_n=13](https://github.com/haykagha/ChessQy/assets/50166655/e152f752-d3d3-454d-9c66-cf04d03cde40)

And the illustration:
![illustration_n=13](https://github.com/haykagha/ChessQy/assets/50166655/94f65cb7-ab29-4b40-b19e-9fdad5ec7db3)

For n = 14, here is the solution:
![found_n=14](https://github.com/haykagha/ChessQy/assets/50166655/49ef0f35-7c86-438d-9fe2-0193ceba7798)

For n = 15, there are 62 attemts for finding solution, but failed to find:
![not_found_n=15](https://github.com/haykagha/ChessQy/assets/50166655/843742b2-fefe-4d8d-a8cd-42762759f298)

I think, that for n > 13 this algorithm should be improved.


