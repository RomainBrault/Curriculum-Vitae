# -*- mode: python -*-
# SCons build file

AddOption('--prefix',
          dest='prefix',
          type='string',
          nargs=1,
          action='store',
          metavar='DIR',
          default='..',
          help='installation prefix')

VariantDir('build_cv/', 'src_cv', duplicate=1)
SConscript('build_cv/SConstruct')
VariantDir('build_resume/', 'src_resume', duplicate=1)
SConscript('build_resume/SConstruct')
