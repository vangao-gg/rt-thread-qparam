from building import *

cwd = GetCurrentDir()
path = [cwd+'/inc']
path += [cwd+'/port']
src  = Glob('src/*.c')
 
group = DefineGroup('qparam', src, depend = ['PKG_USING_QPARAM'], CPPPATH = path)

Return('group')