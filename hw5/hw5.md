# HW5

231830039 李彦谷

## question 1

![image-20260406125249066](/Users/Bgotsd/Library/Application Support/typora-user-images/image-20260406125249066.png)

![image-20260406125313552](/Users/Bgotsd/Library/Application Support/typora-user-images/image-20260406125313552.png)

实际计算中，只需要求解矩阵，然后将比值带入反射/透射系数。

## question2

![image-20260406125328039](/Users/Bgotsd/Library/Application Support/typora-user-images/image-20260406125328039.png)

<img src="/Users/Bgotsd/Library/Application Support/typora-user-images/image-20260406125342592.png" alt="image-20260406125342592" style="zoom:50%;" />

![image-20260406125359068](/Users/Bgotsd/Library/Application Support/typora-user-images/image-20260406125359068.png)

## question3

![image-20260406125449908](/Users/Bgotsd/Library/Application Support/typora-user-images/image-20260406125449908.png)

---



- **验证波速：** 震源作用时间为 5 s。在 $t = 5$ s 时，波刚脱离震源，波峰大约位于 $x = 40$ km 和 $x = 60$ km 处。在 $t = 9$ s 时，左侧波峰移动到了 $x = 24$ km 处。
- 波峰移动距离：$ \Delta x = 40 - 24 = 16 $ km。
- 时间差：$ \Delta t = 9 - 5 = 4 $ s。
- 计算波速：$ v = 16 / 4 = 4 $ km/s，完美吻合题目给定的 $\beta$ 值。

---



- **左端 (0 km自由边界)：** 波发生全反射时，**相位保持不变**。原本是正向的波峰（向上的位移），反射回来后依然是正向的波峰。这从 $t=13$ s 到 $t=17$ s 左侧端点的波形演化可以清晰看到。
- **右端 (100 km固定边界)：** 波发生全反射时，位移被强制为 0，导致**相位反转**。原本是正向的波峰，反射回来后变成了负向的波谷（向下的位移）。这在 $t=13$ s 到 $t=17$ s 时的右侧端点表现得非常明显。

---



- **波的叠加与穿透：** 当两列反射波在中心相遇时，它们遵循**线性叠加原理**。由于左侧反射波是正波，右侧反射波是负波，当它们在大约 $t = 25$ s 于 $x = 50$ km 处相遇时，会发生**相消干涉**，使得该区域的总位移几乎为零。交汇过后，它们互不影响地继续向原本的方向传播，保持各自的形状和速度。