class Solution {
    public int minTimeToVisitAllPoints(int[][] points) {
        int n = 1;
        int time = 0;
        int x = 0;
        int y = 0;
        while(n < points.length){
            x = Math.abs(points[n][0]-points[n-1][0]);
            y = Math.abs(points[n][1]-points[n-1][1]);
            time+= Math.max(x,y);
            n++;
        }
        return time;
    }
}
