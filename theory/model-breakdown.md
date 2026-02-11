# Model Breakdown

## 使用前替换变量

{{field}}                 # 领域（IO / Labor / Macro / Dev / Theory）
{{model_description}}     # 模型文本或设定
{{equilibrium_concept}}   # 均衡概念（Nash / PBE / REE / Competitive）

---

## Prompt

请对以下经济学理论模型进行博士水平的结构化拆解。

领域：{{field}}  
均衡概念：{{equilibrium_concept}}

模型描述：
{{model_description}}

---

## 输出结构（必须严格遵守）

1. Economic Environment  
   - Agents  
   - Information structure  
   - Timing  

2. Formal Setup  
   - Strategy space  
   - Constraints  
   - Objective functions  

3. Equilibrium Characterization  
   - Definition  
   - Necessary conditions  
   - Sufficient conditions  

4. Comparative Statics  

5. Economic Intuition  
   - Mechanism explanation  
   - Welfare implications  

6. Relation to Literature  

要求：
- 不得跳步
- 数学表达必须严谨
- 直觉解释必须独立于公式
