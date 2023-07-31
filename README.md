# riscv_ctb_challenges
Challenge_level1
Challenge1_logical
![Screenshot 2023-07-31 163120](https://github.com/vyomasystems-lab/riscv-ctb-challenge-jaym0311/assets/139430966/2c4d9866-a075-4076-93f8-ee16feab3e52)
There are two errors:-
1) and s7, ra, z4 :- z4 is not a valid register according to base extension
2) andi s5, t1, s0 :- In immediate instructions, there should be an immediate value or offset

 ![Screenshot 2023-07-31 163648](https://github.com/vyomasystems-lab/riscv-ctb-challenge-jaym0311/assets/139430966/906b8ddc-9fb8-4966-a030-35c9c92de185)
 fixing z4 with any valid register  
 fixing andi with and

 Challenge2_loop
 ![Screenshot 2023-07-31 165223](https://github.com/vyomasystems-lab/riscv-ctb-challenge-jaym0311/assets/139430966/70f99c6c-e7be-4ea8-8326-586801c24007)
Assembly program is stuck in a loop and not generating test_spike.dump

![Screenshot 2023-07-31 164849](https://github.com/vyomasystems-lab/riscv-ctb-challenge-jaym0311/assets/139430966/50b65d44-9a68-486c-833d-c8cd426de324)
The loop should terminate after checking 3 sets of test cases

test_spike.dump
![Screenshot 2023-07-31 165951](https://github.com/vyomasystems-lab/riscv-ctb-challenge-jaym0311/assets/139430966/d5fa6609-6d79-40a2-aa15-c8b78837b240)
