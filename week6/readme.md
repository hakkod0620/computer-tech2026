from IPython.display import HTML, display

display(HTML('''
<div style="font-family:Arial;max-width:400px;border-radius:16px;overflow:hidden;box-shadow:0 6px 20px rgba(0,0,0,0.15);">
  
  <div style="background:#06C755;padding:14px 18px;display:flex;align-items:center;gap:18px;">
    <span style="font-size:40px;color:white;cursor:pointer;">←</span>
    <img src="https://api.dicebear.com/7.x/initials/svg?seed=AI" width="32" style="border-radius:60%;">
    <span style="color:white;font-weight:bold;">AI Assistant 🤖</span>
  </div>

  <div style="background:#7ECBB4;padding:18px;min-height:250px;">
    <div style="text-align:center;font-size:11px;color:#fff;margin-bottom:8px;">Today 14:30</div>
    
    <div style="display:flex;margin:6px 0;">
      <div style="background:#fff;padding:10px 14px;border-radius:0 16px 16px 16px;max-width:70%;font-size:13px;">你好</div>
    </div>
    
    <div style="display:flex;justify-content:flex-end;margin:6px 0;">
      <div style="background:#06C755;color:white;padding:10px 14px;border-radius:16px 0 16px 16px;max-width:70%;font-size:13px;">幹嘛? </div>
    </div>
    
    <div style="display:flex;margin:6px 0;">
      <div style="background:#fff;padding:10px 14px;border-radius:0 16px 16px 16px;max-width:70%;font-size:13px;">沒幹嘛</div>
    </div>
    
    <div style="display:flex;justify-content:flex-end;margin:6px 0;">
      <div style="background:#06C755;color:white;padding:10px 14px;border-radius:16px 0 16px 16px;max-width:70%;font-size:13px;">?😎</div>
    </div>
    
    <div style="display:flex;margin:6px 0;">
      <div style="background:#fff;padding:10px 14px;border-radius:0 16px 16px 16px;max-width:80%;font-size:13px;">沒幹嘛</div>
    </div>
  </div> <div style="background:#fff;padding:10px;display:flex;gap:8px;align-items:center;border-top:1px solid #eee;">
    <span style="font-size:20px;">😊</span>
    <input style="flex:1;padding:8px;border:1px solid #ddd;border-radius:20px;outline:none;" placeholder="Message...">
    <span style="font-size:20px;color:#06C755;cursor:pointer;">➤</span>
  </div>
  
</div>
'''))

print("🏆 You just built a LINE clone with HTML+CSS! 你用 HTML+CSS 仿製了 LINE！")
print("   Skills used 使用技能: Flexbox, border-radius, gradients, colors, spacing")
