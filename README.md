```rust
impl Solution {
    pub fn two_sum(nums: Vec<i32>, target: i32) -> Vec<i32> {
        let mut map = std::collections::HashMap::new();
        
        for (i, num) in nums.iter().enumerate() {
            let complement = target - num;
            
            if let Some(&index) = map.get(&complement) {
                return vec![index as i32, i as i32];
            }
            
            map.insert(num, i);
        }
        
        vec![]
    }
}

```

![](nvim.png)

![](vscode.png)

![Stats](https://github-readme-stats.vercel.app/api?username=jbndctf&show_icons=true&hide_title=true&hide_border=true&bg_color=1a1b26&text_color=a9b1d6&title_color=7aa2f7&icon_color=bb9af7&border_radius=12&card_width=450)


![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jbndctf&hide_title=true&layout=compact&hide_border=true&bg_color=1a1b26&text_color=a9b1d6&title_color=7aa2f7&icon_color=bb9af7&border_radius=12&card_width=450)




