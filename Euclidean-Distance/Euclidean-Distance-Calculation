import math

points = [ (5,2),(-1,3),(3,10),(4,-7),(2,19),(13,6) ]

def euclideanDistance(x1,y1,x2,y2):
    return math.sqrt( (x2-x1)**2 + (y2-y1)**2 )

distances = []
for i in range(len(points)):
    for j in range(len(points)):
        if i != j:
            mesafe = euclideanDistance(points[i][0],points[i][1],points[j][0],points[j][1])
            distances.append(mesafe)

min_distance = min(distances)
print("Minimum mesafe: ", min_distance)
