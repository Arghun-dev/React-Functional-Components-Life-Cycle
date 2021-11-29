# React-Functional-Components-Life-Cycle
![Screenshot (29)](https://user-images.githubusercontent.com/53907570/143824451-504b84c6-7644-4d72-aca8-d3273036338a.png)

## 1. Mounting (Run Lazy Initializers)

1. in this stage component initialize the states
2. Render component
3. React Updates DOM
4. Run LayoutEffect (not return) (runs sync)
5. Browser Paints screen
6. Run Effects


## 2. Update

1. first component `renders`
2. React Updates DOM
3. Cleanup Layout Effects
4. Run LayoutEffects
5. Browser Paints Screen
6. Cleanup Effects
7. Run Effects


## 3. unMounting

1. cleanup LayoutEffects
2. cleanup Effects
