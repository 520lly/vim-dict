VIM �ֵ�ֿ�
============

�����������Դʿ⣺

 - c.dic
 - context.dic
 - cpp.dic@	 --> c.dic
 - cs.dic
 - css.dic
 - dot.dic
 - erlang.dic
 - haskell.dic
 - html.dic
 - java.dic
 - javascript.dic
 - lua.dic
 - make.dic
 - masm.dic
 - node.dic
 - php.dic
 - plaintex.dic
 - python.dic
 - ruby.dic
 - scss.dic
 - sh.dic@	 --> zsh.dic
 - snippet.dic
 - tex.dic
 - vim.dic
 - wiki.dic
 - xhtml.dic@	 --> html.dic
 - xslt.dic
 - zsh.dic

���кܴ󲿷ִʿ���Դ�� [https://github.com/Firef0x/vimfiles.git]()����л��


��װ
----

**Vundle** ��ʽ��װ

��`_vimrc`�� /`.vimrc`�м���

	Bundle 'asins/vim-dict'

���� VIM ������`:BundleInstall`������ɰ�װ�ˡ�

**����** ��ʽ��װ

�� dict Ŀ¼�ƶ���`$VIM/vimfiles`Ŀ¼��

Ȼ�������`_vimrc`�� /`.vimrc`�м�����������

	autocmd filetype javascript set dictionary+=$VIMFILES/bundle/vim-dict/dict/javascript.dic
	autocmd filetype javascript set dictionary+=$VIMFILES/bundle/vim-dict/dict/node.dic
	autocmd filetype css set dictionary+=$VIMFILES/bundle/vim-dict/dict/css.dic
	autocmd filetype php set dictionary+=$VIMFILES/bundle/vim-dict/dict/php.dic

ʹ�÷���
---------

������ģʽ�°�`<ctrl-x>_<ctrl-k>`���ɿ�����ʾ������


TODO
-----

  - javascript Ҫ��������һ�ݣ�Ŀǰȱ�ٺܶ� EC 5.0 ������


