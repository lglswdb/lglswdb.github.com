---
layout: post
tags: ["ԭ��","ǰ�˼���","jquery"]
---

jquery�Զ�ѡ��ť(checkbox),��ѡ��ť(radio),����ѡ���(select)�Ĳ������������������ڴ˶Գ��ò�����һ���ܽ�,�Ա���ʹ��ʱ�ܼ�ʱ��ѯ�� 

- **jquery����checkbox**  
    1. ��ȡ��ѡ���checkbox����    `var jqobj = $("input[name=xxx]:checked");`  
    2. �趨ĳ��ťΪѡ��״̬    `$("#xxx").attr("check",true);`   
    
- **jquery����radio**     
    1. ��ȡ��ѡ���radio����     `var jqobj = $("input[name=xxx]:checked");`  
    2. �趨ĳ��ťΪѡ��״̬    `$("#xxx").attr("check",true);`  
    
    
- **jquery����select**
    1. ��ȡ��ѡ����������ֵ   `var selval = $("select[name=xxx]").val();`  
        ע���˷�����Chrome����������ò���$("option:selected").val()�ķ�ʽ����ȡ�Ѿ�ѡ���ֵ��  
    2. ѡ��ĳ����ѡ��    `$("option").attr("select",true);`    
    
    