# machine-learning

- ## General boundary
The general boundary G, with respect to hypothesis space H and training
data D, is the set of maximally general members of H consistent with D.<br>
![image](https://user-images.githubusercontent.com/64849889/141343101-4d2d2b51-c818-4cb7-90c6-9ba54ab0ef7f.png)<br>
Most general ≡ minimal elements of VS<sub>H,D</sub><br>
                  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;≡ "set of necessary conditions"




- ## Specific boundary
The specific boundary S, with respect to hypothesis space H and training
data D, is the set of minimally general (i.e., maximally specific) members of H
consistent with D.
![image](https://user-images.githubusercontent.com/64849889/141343196-c04aba58-7945-46b8-9286-7280eb1418dc.png)<br>
Most general ≡ maximal elements of VS<sub>H,D</sub><br>
              &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;≡ "set of sufficient conditions"

- ## Version space representation theorem
Let X be an arbitrary set of instances and let H be a set of boolean-valued hypotheses defined over X.<br> Let c : X + {O, 1} be an arbitrary target concept defined over X and let D be an arbitrary set of training examples {(x, c(x))}. For all X, H, c, and D such that S and G are well defined, 

![image](https://user-images.githubusercontent.com/64849889/141342831-5dc12c05-0cc7-4e7d-b923-3a6fcabb757f.png)
