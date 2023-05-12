# sine-cosine-tangent
import math
angulo=float(input('Digite o angulo: '))
cos=math.cos(math.radians(angulo))
sin=math.sin(math.radians(angulo))
tang=math.tan(math.radians(angulo))
cosdegree=math.degrees(cos)
sindegree=math.degrees(sin)
tangdegree=math.degrees(tang)
print('Você escolheu o angulo {}!'.format(angulo))
print('Em radianos temos:\n cos de {} = {:.3f}\n seno de {} = {:.3f}\n tangente de {} = {:.3f}'.format(angulo,cos,angulo,sin,angulo,tang))
print('Em graus temos:\n cos de {} = {:.3f}\n seno de {} = {:.3f}\n tangente de {} = {:.3f}'.format(angulo,cosdegree,angulo,sindegree,angulo,tangdegree))
