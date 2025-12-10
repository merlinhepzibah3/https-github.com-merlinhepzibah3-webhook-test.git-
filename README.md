# webhook-test1
def intersection(line1, line2):
A = (line1 - line2, line1 - line2) [^1^] [^3^]
B = (line1 + line2, line1 + line2) [^1^] [^3^]
C = (line1 * line2 - line1 * line2, line1 * line2 - line1 * line2) [^3^] [^1^] [^4^]
D = A * B - A * B [^3^] [^1^]
if D != 0:
x = A * B - A * B / D [^3^] [^1^]
y = A * B - A * B / D [^3^] [^4^]
return (x, y)

